---
title: BezierKnotRecord.BezierKnotRecord
second_title: Aspose.PSD voor .NET API-referentie
description: BezierKnotRecord constructeur. Initialiseert een nieuw exemplaar van hetBezierKnotRecord klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/bezierknotrecord/
---
## BezierKnotRecord() {#constructor}

Initialiseert een nieuw exemplaar van het[`BezierKnotRecord`](../) klasse.

```csharp
public BezierKnotRecord()
```

### Voorbeelden

Het volgende codevoorbeeld biedt klassen om de vectorpadobjecten te manipuleren en laat zien hoe die klassen moeten worden gebruikt.

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
/// De klasse die werk levert tussen <see cref="Layer"/> en <zie cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Creëert de <see cref="VectorPath"/> instantie op basis van bronnen uit de invoerlaag.
    /// </summary>
    /// <param name="psdLayer">De psd-laag.</param>
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
    /// Werkt de invoerlaagbronnen bij van <see cref="VectorPath"/> instantie of vervang deze door een nieuwe padresource en updates.
    /// </summary>
    /// <param name="psdLayer">De psd-laag.</param>
    /// <param name="vectorPath">Het vectorpad.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
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
    /// Verwijdert de gegevens van het vectorpad uit de invoerlaag.
    /// </summary>
    /// <param name="psdLayer">De psd-laag.</param>
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
    /// Werkt brongegevens bij van <see cref="VectorPath"/> voorbeeld.
    /// </summary>
    /// <param name="pathResource">De padbron.</param>
    /// <param name="vogkResource">De gegevensbron voor het ontstaan van vectoren.</param>
    /// <param name="socoResource">De bron met effen kleuren.</param>
    /// <param name="vectorPath">Het vectorpad.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
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
    /// Vervangt bronnen in laag door bijgewerkte of nieuwe.
    /// </summary>
    /// <param name="psdLayer">De psd-laag.</param>
    /// <param name="pathResource">De padbron.</param>
    /// <param name="vogkResource">De gegevensbron voor het ontstaan van vectoren.</param>
    /// <param name="socoResource">De bron met effen kleuren.</param>
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
    /// Vindt de <zie cref="VectorPathDataResource"/> bron in invoerlaagbronnen.
    /// </summary>
    /// <param name="psdLayer">De psd-laag.</param>
    /// <param name="createIfNotExist">Als de bron niet bestaat, dan voor <zie cref="true"/> maakt een nieuwe bron aan, retourneert anders <see cref="null"/>.</param>
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
    /// Vindt de <zie cref="VogkResource"/> bron in invoerlaagbronnen.
    /// </summary>
    /// <param name="psdLayer">De psd-laag.</param>
    /// <param name="createIfNotExist">Als de bron niet bestaat, dan voor <zie cref="true"/> maakt een nieuwe bron aan, retourneert anders <see cref="null"/>.</param>
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
    /// Vindt de <zie cref="SoCoResource"/> bron in invoerlaagbronnen.
    /// </summary>
    /// <param name="psdLayer">De psd-laag.</param>
    /// <param name="createIfNotExist">Als de bron niet bestaat, dan voor <zie cref="true"/> maakt een nieuwe bron aan, retourneert anders <see cref="null"/>.</param>
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
    /// Valideert de laag om mee te werken <see cref="VectorDataProvider"/> klas.
    /// </summary>
    /// <param name="laag"></param>
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
/// De Bézier-curveknoop, deze bevat één ankerpunt en twee controlepunten.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Verhouding tussen afbeelding en padpunt.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Initialiseert een nieuwe instantie van de <see cref="BezierKnot" /> klas.
    /// </summary>
    /// <param name="anchorPoint">Het ankerpunt.</param>
    /// <param name="controlPoint1">Het eerste controlepunt.</param>
    /// <param name="controlPoint2">Het tweede controlepunt.</param>
    /// <param name="isLinked">De waarde die aangeeft of deze knoop gekoppeld is.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Initialiseert een nieuwe instantie van de <see cref="BezierKnot" /> klasse gebaseerd op <zie cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">De <see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Initialiseert een nieuwe instantie van de <see cref="BezierKnot" /> klas.
    /// </summary>
    /// <param name="anchorPoint">Het punt dat anker- en controlepunten moet zijn.</param>
    /// <param name="isLinked">De waarde die aangeeft of deze knoop gekoppeld is.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Haalt of stelt een waarde in die aangeeft of deze instantie is gekoppeld.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Haalt of stelt het eerste controlepunt in.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Haalt of stelt het ankerpunt in.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Haalt of stelt het tweede controlepunt in.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Creëert de instantie van <see cref="BezierKnotRecord"/> op basis van dit exemplaar.
    /// </summary>
    /// <param name="isClosed">Geeft aan of deze knoop een gesloten vorm heeft.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
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
    /// Verschuift deze knooppunten door invoerwaarden.
    /// </summary>
    /// <param name="xOffset">De x-offset.</param>
    /// <param name="yOffset">De y-offset.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Converteert puntwaarden van resource naar normaal.
    /// </summary>
    /// <param name="point">Het punt met waarden uit resource.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Converteert normale puntwaarden naar resourcepunt.
    /// </summary>
    /// <param name="point">Het punt.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// De figuur van de knopen van de Bezier-curve.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Initialiseert een nieuwe instantie van de <see cref="PathShape" /> klas.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Initialiseert een nieuwe instantie van de <see cref="PathShape" /> klasse gebaseerd op <zie cref="VectorPathRecord"/>'s.
    /// </summary>
    /// <param name="lengthRecord">Het lengterecord.</param>
    /// <param name="bezierKnotRecords">De bezier knooprecords.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Haalt of stelt een waarde in die aangeeft of deze instantie gesloten is.
    /// </summary>
    /// <waarde>
    /// <c>waar</c> als deze instantie is gesloten; anders <c>false</c>.
    /// </waarde>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Haalt of stelt de padbewerkingen in (Booleaanse bewerkingen).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Haalt of stelt de index van de huidige padvorm in laag in.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Haalt de punten van de Bezier-curve op.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Creëert de <zie cref="VectorPathRecord"/> records op basis van deze instantie.
    /// </summary>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
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
    /// Initialiseert waarden op basis van invoerrecords.
    /// </summary>
    /// <param name="bezierKnotRecords">De bezier knooprecords.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
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
/// De klasse die vectorpaden bevat.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Initialiseert een nieuw exemplaar van de <see cref="VectorPath" /> klasse gebaseerd op <zie cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">De gegevensbron voor vectorpaden.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Haalt of stelt een waarde in die aangeeft of de vulling begint met alle pixels.
    /// </summary>
    /// <waarde>
    /// De vulling begint met alle pixels.
    /// </waarde>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Krijgt de vectorvormen.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Hiermee wordt de vulkleur van het vectorpad opgehaald of ingesteld.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Haalt de versie op of stelt deze in.
    /// </summary>
    /// <waarde>
    /// De versie.
    /// </waarde>
    public int Version { get; set; }

    /// <summary>
    /// Haalt of stelt een waarde in die aangeeft of deze instantie is uitgeschakeld.
    /// </summary>
    /// <waarde>
    /// <c>waar</c> als deze instantie is uitgeschakeld; anders <c>false</c>.
    /// </waarde>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Haalt of stelt een waarde in die aangeeft of deze instantie niet is gekoppeld.
    /// </summary>
    /// <waarde>
    /// <c>waar</c> als deze instantie niet is gekoppeld; anders <c>false</c>.
    /// </waarde>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Haalt of stelt een waarde in die aangeeft of deze instantie geïnverteerd is.
    /// </summary>
    /// <waarde>
    /// <c>waar</c> als deze instantie wordt omgekeerd; anders <c>false</c>.
    /// </waarde>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Initialiseert waarden op basis van invoer <see cref="VectorPathDataResource"/> bron.
    /// </summary>
    /// <param name="resource">De gegevensbron voor vectorpaden.</param>
    /// <param name="imageSize">De afbeeldingsgrootte om puntcoördinaten te corrigeren.</param>
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

### Zie ook

* class [BezierKnotRecord](../)
* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord/)
* montage [Aspose.PSD](../../../)

---

## BezierKnotRecord(byte[]) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`BezierKnotRecord`](../) klasse.

```csharp
public BezierKnotRecord(byte[] data)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | Byte[] | De recordgegevens. |

### Zie ook

* class [BezierKnotRecord](../)
* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord/)
* montage [Aspose.PSD](../../../)


