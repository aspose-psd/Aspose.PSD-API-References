---
title: "BezierKnotRecord.BezierKnotRecord"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor BezierKnotRecord. Menginisialisasi instance baru dari kelas BezierKnotRecord"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/bezierknotrecord/
---
{{< psd/tize >}}
## BezierKnotRecord() {#constructor}

Menginisialisasi instance baru dari kelas [`BezierKnotRecord`](../).

```csharp
public BezierKnotRecord()
```

## Contoh

Contoh kode berikut menyediakan kelas-kelas untuk memanipulasi objek jalur vektor dan menunjukkan cara menggunakan kelas-kelas tersebut.

```csharp
[C#]

public void CreatingVectorPathExample(string outputPsd = "outputPsd.psd")
{
    using (var psdImage = (PsdImage)Image.Create(new PsdOptions() { Source = new StreamSource(new MemoryStream()), }, 500, 500))
    {
        FillLayer layer = FillLayer.CreateInstance(FillType.Color);
        psdImage.AddLayer(layer);

        VectorPath vectorPath = VectorDataProvider.CreateVectorPathForLayer(layer);
        vectorPath.FillColor = Color.IndianRed;
        PathShape shape = new PathShape();
        shape.Points.Add(new BezierKnot(new PointF(50, 150), true));
        shape.Points.Add(new BezierKnot(new PointF(100, 200), true));
        shape.Points.Add(new BezierKnot(new PointF(0, 200), true));
        vectorPath.Shapes.Add(shape);
        VectorDataProvider.UpdateLayerFromVectorPath(layer, vectorPath, true);

        psdImage.Save(outputPsd);
    }
}

#region Vector path editor (Here placed classes for edit vector paths).

/// <summary>
/// Kelas yang menyediakan kerja antara <see cref=\"Layer\"/> dan <see cref=\"VectorPath\"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Membuat instance <see cref=\"VectorPath\"/> berdasarkan sumber daya dari lapisan input.
    /// </summary>
    /// <param name=\"psdLayer\">Lapisan psd.</param>
    /// <returns>instance <see cref=\"VectorPath\"/> berdasarkan sumber daya dari lapisan input.</returns>
    public static VectorPath CreateVectorPathForLayer(Layer psdLayer)
    {
        ValidateLayer(psdLayer);

        Size imageSize = psdLayer.Container.Size;

        VectorPathDataResource pathResource = FindVectorPathDataResource(psdLayer, true);
        SoCoResource socoResource = FindSoCoResource(psdLayer, true);
        VectorPath vectorPath = new VectorPath(pathResource, imageSize);
        if (socoResource != null)
        {
            vectorPath.FillColor = socoResource.Color;
        }

        return vectorPath;
    }

    /// <summary>
    /// Memperbarui sumber daya lapisan input dari instance <see cref=\"VectorPath\"/>, atau menggantinya dengan sumber daya jalur baru dan memperbarui.
    /// </summary>
    /// <param name=\"psdLayer\">Lapisan psd.</param>
    /// <param name=\"vectorPath\">Jalur vektor.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    public static void UpdateLayerFromVectorPath(Layer psdLayer, VectorPath vectorPath, bool createIfNotExist = false)
    {
        ValidateLayer(psdLayer);

        VectorPathDataResource pathResource = FindVectorPathDataResource(psdLayer, createIfNotExist);
        VogkResource vogkResource = FindVogkResource(psdLayer, createIfNotExist);
        SoCoResource socoResource = FindSoCoResource(psdLayer, createIfNotExist);

        Size imageSize = psdLayer.Container.Size;
        UpdateResources(pathResource, vogkResource, socoResource, vectorPath, imageSize);

        ReplaceVectorPathDataResourceInLayer(psdLayer, pathResource, vogkResource, socoResource);
    }

    /// <summary>
    /// Menghapus data jalur vektor dari lapisan input.
    /// </summary>
    /// <param name=\"psdLayer\">Lapisan psd.</param>
    public static void RemoveVectorPathDataFromLayer(Layer psdLayer)
    {
        List<LayerResource> oldResources = new List<LayerResource>(psdLayer.Resources);
        List<LayerResource> newResources = new List<LayerResource>();
        for (int i = 0; i < oldResources.Count; i++)
        {
            LayerResource resource = oldResources[i];

            if (resource is VectorPathDataResource || resource is VogkResource || resource is SoCoResource)
            {
                continue;
            }
            else
            {
                newResources.Add(resource);
            }
        }

        psdLayer.Resources = newResources.ToArray();
    }

    /// <summary>
    /// Memperbarui data sumber daya dari instance <see cref=\"VectorPath\"/>.
    /// </summary>
    /// <param name=\"pathResource\">Sumber daya jalur.</param>
    /// <param name=\"vogkResource\">Sumber data asal vektor.</param>
    /// <param name=\"socoResource\">Sumber daya warna solid.</param>
    /// <param name=\"vectorPath\">Jalur vektor.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    private static void UpdateResources(VectorPathDataResource pathResource, VogkResource vogkResource, SoCoResource socoResource, VectorPath vectorPath, Size imageSize)
    {
        pathResource.Version = vectorPath.Version;
        pathResource.IsNotLinked = vectorPath.IsNotLinked;
        pathResource.IsDisabled = vectorPath.IsDisabled;
        pathResource.IsInverted = vectorPath.IsInverted;

        List<VectorShapeOriginSettings> originSettings = new List<VectorShapeOriginSettings>();
        List<VectorPathRecord> path = new List<VectorPathRecord>();
        path.Add(new PathFillRuleRecord(null));
        path.Add(new InitialFillRuleRecord(vectorPath.IsFillStartsWithAllPixels));
        for (ushort i = 0; i < vectorPath.Shapes.Count; i++)
        {
            PathShape shape = vectorPath.Shapes[i];
            shape.ShapeIndex = i;
            path.AddRange(shape.ToVectorPathRecords(imageSize));
            originSettings.Add(new VectorShapeOriginSettings() { IsShapeInvalidated = true, OriginIndex = i });
        }

        pathResource.Paths = path.ToArray();
        vogkResource.ShapeOriginSettings = originSettings.ToArray();

        socoResource.Color = vectorPath.FillColor;
    }

    /// <summary>
    /// Mengganti sumber daya di lapisan dengan yang diperbarui atau yang baru.
    /// </summary>
    /// <param name=\"psdLayer\">Lapisan psd.</param>
    /// <param name=\"pathResource\">Sumber daya jalur.</param>
    /// <param name=\"vogkResource\">Sumber data asal vektor.</param>
    /// <param name=\"socoResource\">Sumber daya warna solid.</param>
    private static void ReplaceVectorPathDataResourceInLayer(Layer psdLayer, VectorPathDataResource pathResource, VogkResource vogkResource, SoCoResource socoResource)
    {
        bool pathResourceExist = false;
        bool vogkResourceExist = false;
        bool socoResourceExist = false;

        List<LayerResource> resources = new List<LayerResource>(psdLayer.Resources);
        for (int i = 0; i < resources.Count; i++)
        {
            LayerResource resource = resources[i];
            if (resource is VectorPathDataResource)
            {
                resources[i] = pathResource;
                pathResourceExist = true;
            }
            else if (resource is VogkResource)
            {
                resources[i] = vogkResource;
                vogkResourceExist = true;
            }
            else if (resource is SoCoResource)
            {
                resources[i] = socoResource;
                socoResourceExist = true;
            }
        }

        if (!pathResourceExist)
        {
            resources.Add(pathResource);
        }

        if (!vogkResourceExist)
        {
            resources.Add(vogkResource);
        }

        if (!socoResourceExist)
        {
            resources.Add(socoResource);
        }

        psdLayer.Resources = resources.ToArray();
    }

    /// <summary>
    /// Menemukan sumber daya <see cref=\"VectorPathDataResource\"/> dalam sumber daya lapisan input.
    /// </summary>
    /// <param name=\"psdLayer\">Lapisan psd.</param>
    /// <param name=\"createIfNotExist\">Jika sumber daya tidak ada, maka untuk <see cref=\"true\"/> membuat sumber daya baru, jika tidak mengembalikan <see cref=\"null\"/>.</param>
    /// <returns>Sumber daya <see cref=\"VectorPathDataResource\"/>.</returns>
    private static VectorPathDataResource FindVectorPathDataResource(Layer psdLayer, bool createIfNotExist = false)
    {
        VectorPathDataResource pathResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is VectorPathDataResource)
            {
                pathResource = (VectorPathDataResource)resource;
                break;
            }
        }

        if (createIfNotExist && pathResource == null)
        {
            pathResource = new VmskResource();
        }

        return pathResource;
    }

    /// <summary>
    /// Menemukan sumber daya <see cref=\"VogkResource\"/> dalam sumber daya lapisan input.
    /// </summary>
    /// <param name=\"psdLayer\">Lapisan psd.</param>
    /// <param name=\"createIfNotExist\">Jika sumber daya tidak ada, maka untuk <see cref=\"true\"/> membuat sumber daya baru, jika tidak mengembalikan <see cref=\"null\"/>.</param>
    /// <returns>Sumber daya <see cref=\"VogkResource\"/>.</returns>
    private static VogkResource FindVogkResource(Layer psdLayer, bool createIfNotExist = false)
    {
        VogkResource vogkResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is VogkResource)
            {
                vogkResource = (VogkResource)resource;
                break;
            }
        }

        if (createIfNotExist && vogkResource == null)
        {
            vogkResource = new VogkResource();
        }

        return vogkResource;
    }

    /// <summary>
    /// Menemukan sumber daya <see cref=\"SoCoResource\"/> dalam sumber daya lapisan input.
    /// </summary>
    /// <param name=\"psdLayer\">Lapisan psd.</param>
    /// <param name=\"createIfNotExist\">Jika sumber daya tidak ada, maka untuk <see cref=\"true\"/> membuat sumber daya baru, jika tidak mengembalikan <see cref=\"null\"/>.</param>
    /// <returns>Sumber daya <see cref=\"SoCoResource\"/>.</returns>
    private static SoCoResource FindSoCoResource(Layer psdLayer, bool createIfNotExist = false)
    {
        SoCoResource socoResource = null;
        foreach (var resource in psdLayer.Resources)
        {
            if (resource is SoCoResource)
            {
                socoResource = (SoCoResource)resource;
                break;
            }
        }

        if (createIfNotExist && socoResource == null)
        {
            socoResource = new SoCoResource();
        }

        return socoResource;
    }

    /// <summary>
    /// Memvalidasi lapisan untuk bekerja dengan kelas <see cref=\"VectorDataProvider\"/>.
    /// </summary>
    /// <param name="layer"></param>
    /// <exception cref="ArgumentNullException"></exception>
    private static void ValidateLayer(Layer layer)
    {
        if (layer == null)
        {
            throw new ArgumentNullException("The layer is NULL.");
        }

        if (layer.Container == null || layer.Container.Size.IsEmpty)
        {
            throw new ArgumentNullException("The layer should have a Container with no empty size.");
        }
    }
}

/// <summary>
/// Knot kurva Bezier, berisi satu titik jangkar dan dua titik kontrol.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Rasio titik gambar ke jalur.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Menginisialisasi instance baru dari kelas <see cref="BezierKnot" />.
    /// </summary>
    /// <param name="anchorPoint">Titik jangkar.</param>
    /// <param name="controlPoint1">Titik kontrol pertama.</param>
    /// <param name="controlPoint2">Titik kontrol kedua.</param>
    /// <param name="isLinked">Nilai yang menunjukkan apakah knot ini terhubung.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Menginisialisasi instance baru dari kelas <see cref="BezierKnot" /> berdasarkan <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">Objek <see cref="BezierKnotRecord"/>.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Menginisialisasi instance baru dari kelas <see cref="BezierKnot" />.
    /// </summary>
    /// <param name="anchorPoint">Titik yang menjadi jangkar dan titik kontrol.</param>
    /// <param name="isLinked">Nilai yang menunjukkan apakah knot ini terhubung.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terhubung.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur titik kontrol pertama.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur titik jangkar.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur titik kontrol kedua.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Membuat instance dari <see cref="BezierKnotRecord"/> berdasarkan instance ini.
    /// </summary>
    /// <param name="isClosed">Menunjukkan apakah knot ini berada dalam bentuk tertutup.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    /// <returns>Instance dari <see cref="BezierKnotRecord"/> berdasarkan instance ini.</returns>
    public BezierKnotRecord ToBezierKnotRecord(bool isClosed, Size imageSize)
    {
        BezierKnotRecord record = new BezierKnotRecord();
        record.Points = new Point[]
        {
            PointFToResourcePoint(this.ControlPoint1, imageSize),
            PointFToResourcePoint(this.AnchorPoint, imageSize),
            PointFToResourcePoint(this.ControlPoint2, imageSize),
        };
        record.IsLinked = this.IsLinked;
        record.IsClosed = isClosed;

        return record;
    }

    /// <summary>
    /// Menggeser titik-titik knot ini dengan nilai input.
    /// </summary>
    /// <param name="xOffset">Offset x.</param>
    /// <param name="yOffset">Offset y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Mengonversi nilai titik dari sumber ke normal.
    /// </summary>
    /// <param name="point">Titik dengan nilai dari sumber.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    /// <returns>Titik yang telah dikonversi ke normal.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Mengonversi nilai titik normal menjadi titik sumber daya.
    /// </summary>
    /// <param name="point">Titik tersebut.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    /// <returns>Titik dengan nilai untuk sumber daya.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Gambar dari simpul-simpul kurva Bezier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Menginisialisasi instance baru dari kelas <see cref="PathShape" />.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Menginisialisasi instance baru dari kelas <see cref="PathShape" /> berdasarkan <see cref="VectorPathRecord"/>'.
    /// </summary>
    /// <param name="lengthRecord">Catatan panjang.</param>
    /// <param name="bezierKnotRecords">Catatan simpul bezier.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tertutup.
    /// </summary>
    /// <value>
    ///   <c>true</c> jika instance ini tertutup; selainnya, <c>false</c>
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur operasi jalur (operasi Boolean).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur indeks bentuk jalur saat ini dalam lapisan.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Mendapatkan titik-titik kurva Bezier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Membuat catatan <see cref="VectorPathRecord"/> berdasarkan instance ini.
    /// </summary>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    /// <returns>Mengembalikan satu <see cref="LengthRecord"/> dan <see cref="BezierKnotRecord"/> untuk setiap titik dalam instance ini.</returns>
    public IEnumerable<VectorPathRecord> ToVectorPathRecords(Size imageSize)
    {
        List<VectorPathRecord> shapeRecords = new List<VectorPathRecord>();

        LengthRecord lengthRecord = new LengthRecord();
        lengthRecord.IsClosed = this.IsClosed;
        lengthRecord.BezierKnotRecordsCount = this.Points.Count;
        lengthRecord.PathOperations = this.PathOperations;
        lengthRecord.ShapeIndex = this.ShapeIndex;
        shapeRecords.Add(lengthRecord);

        foreach (var bezierKnot in this.Points)
        {
            shapeRecords.Add(bezierKnot.ToBezierKnotRecord(this.IsClosed, imageSize));
        }

        return shapeRecords;
    }

    /// <summary>
    /// Menginisialisasi nilai berdasarkan catatan masukan.
    /// </summary>
    /// <param name="bezierKnotRecords">Catatan simpul bezier.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    private void InitFromResources(IEnumerable<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    {
        List<BezierKnot> newPoints = new List<BezierKnot>();

        foreach (var record in bezierKnotRecords)
        {
            newPoints.Add(new BezierKnot(record, imageSize));
        }

        this.Points = newPoints;
    }
}

/// <summary>
/// Kelas yang berisi jalur vektor.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Menginisialisasi instance baru dari kelas <see cref="VectorPath" /> berdasarkan <see cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">Sumber data jalur vektor.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Mendapatkan atau mengatur nilai yang menunjukkan apakah is fill dimulai dengan semua piksel.
    /// </summary>
    /// <value>
    /// is fill dimulai dengan semua piksel.
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Mendapatkan bentuk vektor.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Mendapatkan atau mengatur warna isian jalur vektor.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur versi.
    /// </summary>
    /// <value>
    /// Versi.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan.
    /// </summary>
    /// <value>
    ///   <c>true</c> jika instance ini dinonaktifkan; jika tidak, <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung.
    /// </summary>
    /// <value>
    ///   <c>true</c> jika instance ini tidak terhubung; jika tidak, <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik.
    /// </summary>
    /// <value>
    ///   <c>true</c> jika instance ini terbalik; jika tidak, <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Menginisialisasi nilai berdasarkan sumber <see cref=\"VectorPathDataResource\"/> input.
    /// </summary>
    /// <param name=\"resource\">Sumber data jalur vektor.</param>
    /// <param name=\"imageSize\">Ukuran gambar untuk memperbaiki konversi koordinat titik.</param>
    private void InitFromResource(VectorPathDataResource resource, Size imageSize)
    {
        List<PathShape> newShapes = new List<PathShape>();
        InitialFillRuleRecord initialFillRuleRecord = null;
        LengthRecord lengthRecord = null;
        List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

        foreach (var pathRecord in resource.Paths)
        {
            if (pathRecord is LengthRecord)
            {
                if (bezierKnotRecords.Count > 0)
                {
                    newShapes.Add(new PathShape(lengthRecord, bezierKnotRecords, imageSize));
                    lengthRecord = null;
                    bezierKnotRecords.Clear();
                }

                lengthRecord = (LengthRecord)pathRecord;
            }
            else if (pathRecord is BezierKnotRecord)
            {
                bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
            }
            else if (pathRecord is InitialFillRuleRecord)
            {
                initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            }
        }

        if (bezierKnotRecords.Count > 0)
        {
            newShapes.Add(new PathShape(lengthRecord, bezierKnotRecords, imageSize));
            lengthRecord = null;
            bezierKnotRecords.Clear();
        }

        this.IsFillStartsWithAllPixels = initialFillRuleRecord != null ? initialFillRuleRecord.IsFillStartsWithAllPixels : false;
        this.Shapes = newShapes;

        this.Version = resource.Version;
        this.IsNotLinked = resource.IsNotLinked;
        this.IsDisabled = resource.IsDisabled;
        this.IsInverted = resource.IsInverted;
    }
}

#endregion
```

### Lihat Juga

* class [BezierKnotRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## BezierKnotRecord(byte[]) {#constructor_1}

Menginisialisasi instance baru dari kelas [`BezierKnotRecord`](../).

```csharp
public BezierKnotRecord(byte[] data)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | Byte[] | Data rekaman. |

### Lihat Juga

* class [BezierKnotRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


