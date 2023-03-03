---
title: InitialFillRuleRecord.InitialFillRuleRecord
second_title: Aspose.PSD untuk Referensi .NET API
description: InitialFillRuleRecord konstruktor. Menginisialisasi instance baru dariInitialFillRuleRecord kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.core.vectorpaths/initialfillrulerecord/initialfillrulerecord/
---
## InitialFillRuleRecord() {#constructor}

Menginisialisasi instance baru dari[`InitialFillRuleRecord`](../) kelas.

```csharp
public InitialFillRuleRecord()
```

### Lihat juga

* class [InitialFillRuleRecord](../)
* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../initialfillrulerecord/)
* perakitan [Aspose.PSD](../../../)

---

## InitialFillRuleRecord(bool) {#constructor_1}

Menginisialisasi instance baru dari[`InitialFillRuleRecord`](../) kelas.

```csharp
public InitialFillRuleRecord(bool isFillStartsWithAllPixels)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| isFillStartsWithAllPixels | Boolean | Pengisian dimulai dengan semua piksel. |

### Contoh

Contoh kode berikut menyediakan kelas untuk memanipulasi objek jalur vektor dan menunjukkan cara menggunakan kelas tersebut.

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
/// Kelas yang menyediakan pekerjaan antara <lihat cref="Lapisan"/> dan <lihat cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Membuat <lihat cref="VectorPath"/> instance berdasarkan sumber daya dari lapisan input.
    /// </summary>
    /// <param name="psdLayer">Lapisan psd.</param>
    /// <returns>the <see cref="VectorPath"/> instance based on resources from input layer.</returns>
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
    /// Memperbarui sumber daya lapisan masukan dari <lihat cref="VectorPath"/> misalnya, atau ganti dengan sumber daya jalur baru dan pembaruan.
    /// </summary>
    /// <param name="psdLayer">Lapisan psd.</param>
    /// <param name="vectorPath">Jalur vektor.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
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
    /// Menghapus data jalur vektor dari lapisan masukan.
    /// </summary>
    /// <param name="psdLayer">Lapisan psd.</param>
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
    /// Memperbarui data sumber daya dari <lihat cref="VectorPath"/> contoh.
    /// </summary>
    /// <param name="pathResource">Sumber daya jalur.</param>
    /// <param name="vogkResource">Sumber data originasi vektor.</param>
    /// <param name="socoResource">Sumber daya warna solid.</param>
    /// <param name="vectorPath">Jalur vektor.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
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
    /// Mengganti sumber daya dalam lapisan dengan yang diperbarui atau yang baru.
    /// </summary>
    /// <param name="psdLayer">Lapisan psd.</param>
    /// <param name="pathResource">Sumber daya jalur.</param>
    /// <param name="vogkResource">Sumber data originasi vektor.</param>
    /// <param name="socoResource">Sumber daya warna solid.</param>
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
    /// Menemukan <lihat cref="VectorPathDataResource"/> sumber daya dalam sumber daya lapisan input.
    /// </summary>
    /// <param name="psdLayer">Lapisan psd.</param>
    /// <param name="createIfNotExist">Jika sumber daya tidak ada, maka untuk <lihat cref="true"/> buat sumber daya baru, jika tidak kembalikan <lihat cref="null"/>.</param>
    /// <returns>The <see cref="VectorPathDataResource"/> resource.</returns>
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
    /// Menemukan <lihat cref="VogkResource"/> sumber daya dalam sumber daya lapisan input.
    /// </summary>
    /// <param name="psdLayer">Lapisan psd.</param>
    /// <param name="createIfNotExist">Jika sumber daya tidak ada, maka untuk <lihat cref="true"/> buat sumber daya baru, jika tidak kembalikan <lihat cref="null"/>.</param>
    /// <returns>The <see cref="VogkResource"/> resource.</returns>
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
    /// Menemukan <lihat cref="SoCoResource"/> sumber daya dalam sumber daya lapisan masukan.
    /// </summary>
    /// <param name="psdLayer">Lapisan psd.</param>
    /// <param name="createIfNotExist">Jika sumber daya tidak ada, maka untuk <lihat cref="true"/> buat sumber daya baru, jika tidak kembalikan <lihat cref="null"/>.</param>
    /// <returns>The <see cref="SoCoResource"/> resource.</returns>
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
    /// Memvalidasi lapisan untuk bekerja dengan <lihat cref="VectorDataProvider"/> kelas.
    /// </summary>
    /// <nama param="lapisan"></param>
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
/// Simpul kurva Bezier, berisi satu titik jangkar dan dua titik kontrol.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Gambar ke rasio titik jalur.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Menginisialisasi instance baru dari <lihat cref="BezierKnot" /> kelas.
    /// </summary>
    /// <param name="anchorPoint">Titik jangkar.</param>
    /// <param name="controlPoint1">Titik kontrol pertama.</param>
    /// <param name="controlPoint2">Titik kontrol kedua.</param>
    /// <param name="isLinked">Nilai yang menunjukkan apakah simpul ini terhubung.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Menginisialisasi instance baru dari <lihat cref="BezierKnot" /> kelas berdasarkan <lihat cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord"><lihat cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Menginisialisasi instance baru dari <lihat cref="BezierKnot" /> kelas.
    /// </summary>
    /// <param name="anchorPoint">Titik yang akan dijadikan anchor dan titik kontrol.</param>
    /// <param name="isLinked">Nilai yang menunjukkan apakah simpul ini terhubung.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini ditautkan.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Mendapat atau menyetel titik kontrol pertama.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Mendapat atau menetapkan titik jangkar.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Mendapat atau menyetel titik kontrol kedua.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Membuat instance dari <see cref="BezierKnotRecord"/> berdasarkan contoh ini.
    /// </summary>
    /// <param name="isClosed">Menunjukkan apakah simpul ini dalam bentuk tertutup.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
    /// <returns>The instance of <see cref="BezierKnotRecord"/> based on this instance.</returns>
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
    /// Menggeser titik simpul ini dengan nilai masukan.
    /// </summary>
    /// <param name="xOffset">X offset.</param>
    /// <param name="yOffset">Offset y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Mengonversi nilai poin dari resource ke normal.
    /// </summary>
    /// <param name="point">Titik dengan nilai dari resource.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Mengubah nilai titik normal menjadi titik sumber daya.
    /// </summary>
    /// <param name="titik">Titik.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Sosok dari simpul kurva Bezier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Menginisialisasi instance baru dari <see cref="PathShape" /> kelas.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Menginisialisasi instance baru dari <see cref="PathShape" /> kelas berdasarkan <lihat cref="VectorPathRecord"/>'s.
    /// </summary>
    /// <param name="lengthRecord">Catatan panjang.</param>
    /// <param name="bezierKnotRecords">Simpul bezier mencatat.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini ditutup.
    /// </summary>
    /// <nilai>
    /// <c>benar</c> jika instance ini ditutup; jika tidak, <c>salah</c>.
    /// </nilai>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Mendapat atau menyetel operasi jalur (operasi Boolean).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Mendapat atau menetapkan indeks bentuk jalur saat ini dalam lapisan.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Mendapatkan poin dari kurva Bezier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Membuat <lihat cref="VectorPathRecord"/> catatan berdasarkan contoh ini.
    /// </summary>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
    /// <returns>Returns one <see cref="LengthRecord"/> and <see cref="BezierKnotRecord"/> for each point in this instance.</returns>
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
    /// Menginisialisasi nilai berdasarkan catatan input.
    /// </summary>
    /// <param name="bezierKnotRecords">Simpul bezier mencatat.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
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
    /// Menginisialisasi instance baru dari <lihat cref="VectorPath" /> kelas berdasarkan <lihat cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">Sumber data jalur vektor.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Mendapat atau menetapkan nilai yang menunjukkan apakah isian dimulai dengan semua piksel.
    /// </summary>
    /// <nilai>
    /// isian dimulai dengan semua piksel.
    /// </nilai>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Mendapatkan bentuk vektor.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Mendapat atau menyetel warna isian jalur vektor.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Mendapatkan atau menyetel versi.
    /// </summary>
    /// <nilai>
    /// Versi.
    /// </nilai>
    public int Version { get; set; }

    /// <summary>
    /// Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini dinonaktifkan.
    /// </summary>
    /// <nilai>
    /// <c>benar</c> jika instance ini dinonaktifkan; jika tidak, <c>salah</c>.
    /// </nilai>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini tidak ditautkan.
    /// </summary>
    /// <nilai>
    /// <c>benar</c> jika instance ini tidak ditautkan; jika tidak, <c>salah</c>.
    /// </nilai>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini terbalik.
    /// </summary>
    /// <nilai>
    /// <c>benar</c> jika hal ini terbalik; jika tidak, <c>salah</c>.
    /// </nilai>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Menginisialisasi nilai berdasarkan masukan <lihat cref="VectorPathDataResource"/> sumber.
    /// </summary>
    /// <param name="resource">Sumber data jalur vektor.</param>
    /// <param name="imageSize">Ukuran gambar untuk memperbaiki koordinat titik konversi.</param>
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

### Lihat juga

* class [InitialFillRuleRecord](../)
* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../initialfillrulerecord/)
* perakitan [Aspose.PSD](../../../)

---

## InitialFillRuleRecord(byte[]) {#constructor_2}

Menginisialisasi instance baru dari[`InitialFillRuleRecord`](../) kelas.

```csharp
public InitialFillRuleRecord(byte[] data)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| data | Byte[] | Data rekaman. |

### Lihat juga

* class [InitialFillRuleRecord](../)
* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../initialfillrulerecord/)
* perakitan [Aspose.PSD](../../../)


