---
title: "VsmsResource.VsmsResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "VsmsResource yapıcı. VsmsResource sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/vsmsresource/
---
{{< psd/tize >}}
## VsmsResource(byte[]) {#constructor_1}

[`VsmsResource`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public VsmsResource(byte[] data)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | Byte[] | Kaynak veri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Geçersiz Vsms Kaynak değeri |

### Ayrıca Bakınız

* class [VsmsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## VsmsResource() {#constructor}

[`VsmsResource`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public VsmsResource()
```

## Örnekler

Aşağıdaki kod örneği, vektör yol nesnelerini manipüle etmek için sınıflar sağlar ve bu sınıfların nasıl kullanılacağını gösterir.

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
/// <see cref=\"Layer\"/> ve <see cref=\"VectorPath\"/> arasında çalışmayı sağlayan sınıf.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Giriş katmanından gelen kaynaklara dayanarak <see cref=\"VectorPath\"/> örneğini oluşturur.
    /// </summary>
    /// <param name=\"psdLayer\">psd katmanı.</param>
    /// <returns>giriş katmanından gelen kaynaklara dayanarak <see cref=\"VectorPath\"/> örneği.</returns>
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
    /// Giriş katmanı kaynaklarını <see cref=\"VectorPath\"/> örneğinden günceller veya yeni yol kaynağıyla değiştirir ve günceller.
    /// </summary>
    /// <param name=\"psdLayer\">psd katmanı.</param>
    /// <param name=\"vectorPath\">Vektör yolu.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
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
    /// Vektör yol verisini giriş katmanından kaldırır.
    /// </summary>
    /// <param name=\"psdLayer\">psd katmanı.</param>
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
    /// Kaynak verilerini <see cref=\"VectorPath\"/> örneğinden günceller.
    /// </summary>
    /// <param name=\"pathResource\">Yol kaynağı.</param>
    /// <param name=\"vogkResource\">Vektör başlangıç veri kaynağı.</param>
    /// <param name=\"socoResource\">Katı renk kaynağı.</param>
    /// <param name=\"vectorPath\">Vektör yolu.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
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
    /// Katmandaki kaynakları güncellenmiş veya yeni olanlarla değiştirir.
    /// </summary>
    /// <param name=\"psdLayer\">psd katmanı.</param>
    /// <param name=\"pathResource\">Yol kaynağı.</param>
    /// <param name=\"vogkResource\">Vektör başlangıç veri kaynağı.</param>
    /// <param name=\"socoResource\">Katı renk kaynağı.</param>
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
    /// Giriş katmanı kaynaklarında <see cref=\"VectorPathDataResource\"/> kaynağını bulur.
    /// </summary>
    /// <param name=\"psdLayer\">psd katmanı.</param>
    /// <param name=\"createIfNotExist\">Kaynak mevcut değilse, <see cref=\"true\"/> için yeni bir kaynak oluşturur, aksi takdirde <see cref=\"null\"/> döndürür.</param>
    /// <returns><see cref=\"VectorPathDataResource\"/> kaynağı.</returns>
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
    /// Giriş katmanı kaynaklarında <see cref=\"VogkResource\"/> kaynağını bulur.
    /// </summary>
    /// <param name=\"psdLayer\">psd katmanı.</param>
    /// <param name=\"createIfNotExist\">Kaynak mevcut değilse, <see cref=\"true\"/> için yeni bir kaynak oluşturur, aksi takdirde <see cref=\"null\"/> döndürür.</param>
    /// <returns><see cref=\"VogkResource\"/> kaynağı.</returns>
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
    /// Giriş katmanı kaynaklarında <see cref=\"SoCoResource\"/> kaynağını bulur.
    /// </summary>
    /// <param name=\"psdLayer\">psd katmanı.</param>
    /// <param name=\"createIfNotExist\">Kaynak mevcut değilse, <see cref=\"true\"/> için yeni bir kaynak oluşturur, aksi takdirde <see cref=\"null\"/> döndürür.</param>
    /// <returns><see cref=\"SoCoResource\"/> kaynağı.</returns>
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
    /// Katmanı <see cref=\"VectorDataProvider\"/> sınıfı ile çalışacak şekilde doğrular.
    /// </summary>
    /// <param name=\"layer\"></param>
    /// <exception cref=\"ArgumentNullException\"></exception>
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
/// Bezier eğri düğümü, bir tutma noktası ve iki kontrol noktası içerir.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Görüntü ile yol noktası oranı.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// <see cref=\"BezierKnot\" /> sınıfının yeni bir örneğini başlatır.
    /// </summary>
    /// <param name=\"anchorPoint\">Tutma noktası.</param>
    /// <param name=\"controlPoint1\">İlk kontrol noktası.</param>
    /// <param name=\"controlPoint2\">İkinci kontrol noktası.</param>
    /// <param name=\"isLinked\">Bu düğümün bağlı olup olmadığını gösteren değer.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Yeni bir <see cref=\"BezierKnot\" /> sınıfı örneğini <see cref=\"BezierKnotRecord\"/> temel alarak başlatır.
    /// </summary>
    /// <param name=\"bezierKnotRecord\">Bu <see cref=\"BezierKnotRecord\"/>.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// <see cref=\"BezierKnot\" /> sınıfının yeni bir örneğini başlatır.
    /// </summary>
    /// <param name=\"anchorPoint\">Bağlantı ve kontrol noktaları olacak nokta.</param>
    /// <param name=\"isLinked\">Bu düğümün bağlı olup olmadığını gösteren değer.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Bu örneğin bağlı olup olmadığını gösteren bir değeri alır veya ayarlar.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// İlk kontrol noktasını alır veya ayarlar.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Bağlantı noktasını alır veya ayarlar.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// İkinci kontrol noktasını alır veya ayarlar.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Bu örnek temel alınarak <see cref=\"BezierKnotRecord\"/> örneğini oluşturur.
    /// </summary>
    /// <param name=\"isClosed\">Bu düğümün kapalı bir şekil içinde olup olmadığını gösterir.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
    /// <returns>Bu örnek temel alınarak <see cref=\"BezierKnotRecord\"/> örneği.</returns>
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
    /// Bu düğüm noktalarını giriş değerleriyle kaydırır.
    /// </summary>
    /// <param name=\"xOffset\">x kayması.</param>
    /// <param name=\"yOffset\">y kayması.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Nokta değerlerini kaynaktan normale dönüştürür.
    /// </summary>
    /// <param name=\"point\">Kaynaktan gelen değerlerle nokta.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
    /// <returns>Normale dönüştürülmüş nokta.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Normal nokta değerlerini kaynak noktaya dönüştürür.
    /// </summary>
    /// <param name=\"point\">Nokta.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
    /// <returns>Kaynak için değerleri içeren nokta.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Bezier eğrisinin düğümlerinden oluşan şekil.
/// </summary>
public class PathShape
{
    /// <summary>
    /// <see cref=\"PathShape\" /> sınıfının yeni bir örneğini başlatır.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// <see cref=\"PathShape\" /> sınıfının <see cref=\"VectorPathRecord\"/> temel alınarak yeni bir örneğini başlatır.
    /// </summary>
    /// <param name=\"lengthRecord\">Uzunluk kaydı.</param>
    /// <param name=\"bezierKnotRecords\">Bezier düğüm kayıtları.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Bu örneğin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar.
    /// </summary>
    /// <value>
    ///   <c>true</c> bu örnek kapalıysa; aksi takdirde <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Yol işlemlerini (Boolean işlemler) alır veya ayarlar.
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Katmandaki mevcut yol şeklinin indeksini alır veya ayarlar.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Bezier eğrisinin noktalarını alır.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Bu örneğe dayanarak <see cref=\"VectorPathRecord\"/> kayıtlarını oluşturur.
    /// </summary>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
    /// <returns>Bu örnekteki her nokta için bir <see cref=\"LengthRecord\"/> ve bir <see cref=\"BezierKnotRecord\"/> döndürür.</returns>
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
    /// Girdi kayıtlarına dayanarak değerleri başlatır.
    /// </summary>
    /// <param name=\"bezierKnotRecords\">Bezier düğüm kayıtları.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
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
/// Vektör yollarını içeren sınıf.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// <see cref=\"VectorPathDataResource\"/> temel alınarak <see cref=\"VectorPath\" /> sınıfının yeni bir örneğini başlatır.
    /// </summary>
    /// <param name=\"vectorPathDataResource\">Vektör yol veri kaynağı.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Doldurmanın tüm piksellerle başlayıp başlamadığını gösteren bir değeri alır veya ayarlar.
    /// </summary>
    /// <value>
    /// Doldurma tüm piksellerle başlar.
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Vektör şekillerini alır.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Vektör yol doldurma rengini alır veya ayarlar.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Sürümü alır veya ayarlar.
    /// </summary>
    /// <value>
    /// Sürüm.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// Bu örneğin devre dışı bırakılıp bırakılmadığını gösteren bir değeri alır veya ayarlar.
    /// </summary>
    /// <value>
    ///   <c>true</c> bu örnek devre dışıysa; aksi takdirde <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Bu örneğin bağlı olmama durumunu gösteren bir değeri alır veya ayarlar.
    /// </summary>
    /// <value>
    ///   <c>true</c> bu örnek bağlı değilse; aksi takdirde <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Bu örneğin ters çevrilip çevrilmediğini gösteren bir değeri alır veya ayarlar.
    /// </summary>
    /// <value>
    ///   <c>true</c> bu örnek ters çevrilmişse; aksi takdirde <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Giriş <see cref="VectorPathDataResource"/> kaynağına dayalı değerleri başlatır.
    /// </summary>
    /// <param name="resource">Vektör yol veri kaynağı.</param>
    /// <param name=\"imageSize\">Nokta koordinatlarını dönüştürmeyi düzeltmek için görüntü boyutu.</param>
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

### Ayrıca Bakınız

* class [VsmsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


