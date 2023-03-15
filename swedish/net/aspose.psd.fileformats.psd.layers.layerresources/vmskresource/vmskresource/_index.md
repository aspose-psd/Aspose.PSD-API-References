---
title: VmskResource.VmskResource
second_title: Aspose.PSD för .NET API-referens
description: VmskResource byggare. Initierar en ny instans avVmskResource class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
## VmskResource(byte[]) {#constructor_1}

Initierar en ny instans av[`VmskResource`](../) class.

```csharp
public VmskResource(byte[] data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | Byte[] | Resursdata. |

### Undantag

| undantag | skick |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Ogiltigt Vmsk-resursvärde |

### Se även

* class [VmskResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* hopsättning [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

Initierar en ny instans av[`VmskResource`](../) class.

```csharp
public VmskResource()
```

### Exempel

Följande kodexempel tillhandahåller klasser för att manipulera vektorvägsobjekten och visar hur man använder dessa klasser.

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
/// Klassen som ger arbete mellan <see cref="Layer"/> och <se cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Skapar <see cref="VectorPath"/> instans baserad på resurser från indatalager.
    /// </summary>
    /// <param name="psdLayer">Psd-lagret.</param>
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
    /// Uppdaterar indatalagerresurserna från <see cref="VectorPath"/> instans, eller ersätt med ny sökvägsresurs och uppdateringar.
    /// </summary>
    /// <param name="psdLayer">Psd-lagret.</param>
    /// <param name="vectorPath">Vektorsökvägen.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
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
    /// Tar bort vektorsökvägsdata från indatalagret.
    /// </summary>
    /// <param name="psdLayer">Psd-lagret.</param>
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
    /// Uppdaterar resursdata från <see cref="VectorPath"/> exempel.
    /// </summary>
    /// <param name="pathResource">Sökvägsresursen.</param>
    /// <param name="vogkResource">Vektoruppkomstdataresursen.</param>
    /// <param name="socoResource">Enfärgsresursen.</param>
    /// <param name="vectorPath">Vektorsökvägen.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
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
    /// Ersätter resurser i lager med uppdaterade eller nya.
    /// </summary>
    /// <param name="psdLayer">Psd-lagret.</param>
    /// <param name="pathResource">Sökvägsresursen.</param>
    /// <param name="vogkResource">Vektoruppkomstdataresursen.</param>
    /// <param name="socoResource">Enfärgsresursen.</param>
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
    /// Hittar <see cref="VectorPathDataResource"/> resurs i indatalagerresurser.
    /// </summary>
    /// <param name="psdLayer">Psd-lagret.</param>
    /// <param name="createIfNotExist">Om resursen inte finns, då för <se cref="true"/> skapar en ny resurs, annars returnerar <see cref="null"/>.</param>
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
    /// Hittar <see cref="VogkResource"/> resurs i indatalagerresurser.
    /// </summary>
    /// <param name="psdLayer">Psd-lagret.</param>
    /// <param name="createIfNotExist">Om resursen inte finns, då för <se cref="true"/> skapar en ny resurs, annars returnerar <see cref="null"/>.</param>
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
    /// Hittar <see cref="SoCoResource"/> resurs i indatalagerresurser.
    /// </summary>
    /// <param name="psdLayer">Psd-lagret.</param>
    /// <param name="createIfNotExist">Om resursen inte finns, då för <se cref="true"/> skapar en ny resurs, annars returnerar <see cref="null"/>.</param>
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
    /// Validerar lagret som ska fungera med <see cref="VectorDataProvider"/> klass.
    /// </summary>
    /// <param name="lager"></param>
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
/// Bezier-kurvknuten, den innehåller en ankarpunkt och två kontrollpunkter.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Bild till vägpunktsförhållande.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Initierar en ny instans av <see cref="BezierKnot" /> klass.
    /// </summary>
    /// <param name="anchorPoint">Förankringspunkten.</param>
    /// <param name="controlPoint1">Den första kontrollpunkten.</param>
    /// <param name="controlPoint2">Den andra kontrollpunkten.</param>
    /// <param name="isLinked">Värdet som anger om denna knut är länkad.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Initierar en ny instans av <see cref="BezierKnot" /> klass baserad på <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord"><see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Initierar en ny instans av <see cref="BezierKnot" /> klass.
    /// </summary>
    /// <param name="anchorPoint">Punkten som ska vara ankar- och kontrollpunkter.</param>
    /// <param name="isLinked">Värdet som anger om denna knut är länkad.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Hämtar eller ställer in ett värde som anger om denna instans är länkad.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Hämtar eller ställer in den första kontrollpunkten.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Hämtar eller ställer in ankarpunkten.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Hämtar eller ställer in den andra kontrollpunkten.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Skapar instansen av <see cref="BezierKnotRecord"/> baserat på detta fall.
    /// </summary>
    /// <param name="isClosed">Anger om denna knut är i sluten form.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
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
    /// Förskjuter denna knutpunkter med ingångsvärden.
    /// </summary>
    /// <param name="xOffset">X-offset.</param>
    /// <param name="yOffset">y-offset.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Konverterar poängvärden från resurs till normal.
    /// </summary>
    /// <param name="punkt">Punkten med värden från resurs.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Konverterar normala poängvärden till resurspunkt.
    /// </summary>
    /// <param name="punkt">Punkten.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Figuren från knutarna på Bezier-kurvan.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Initierar en ny instans av <see cref="PathShape" /> klass.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Initierar en ny instans av <see cref="PathShape" /> klass baserad på <se cref="VectorPathRecord"/>s.
    /// </summary>
    /// <param name="lengthRecord">Längdposten.</param>
    /// <param name="bezierKnotRecords">Bezier-knuten registrerar.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Hämtar eller ställer in ett värde som indikerar om denna instans är stängd.
    /// </summary>
    /// <värde>
    /// <c>sant</c> om denna instans är stängd; annars, <c>false</c>.
    /// </värde>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Hämtar eller ställer in sökvägsoperationerna (booleska operationer).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Hämtar eller ställer in index för aktuell vägform i lager.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Hämtar punkterna för Bezier-kurvan.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Skapar <see cref="VectorPathRecord"/> poster baserade på denna instans.
    /// </summary>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
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
    /// Initierar ett värde baserat på indataposter.
    /// </summary>
    /// <param name="bezierKnotRecords">Bezier-knuten registrerar.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
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
/// Klassen som innehåller vektorbanor.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Initierar en ny instans av <see cref="VectorPath" /> klass baserad på <see cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">Vektorsökvägsdataresursen.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Hämtar eller ställer in ett värde som anger om fyllningen börjar med alla pixlar.
    /// </summary>
    /// <värde>
    /// Fyllningen börjar med alla pixlar.
    /// </värde>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Hämtar vektorformerna.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Hämtar eller ställer in vektorns fyllnadsfärg.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Hämtar eller ställer in versionen.
    /// </summary>
    /// <värde>
    /// Versionen.
    /// </värde>
    public int Version { get; set; }

    /// <summary>
    /// Hämtar eller ställer in ett värde som anger om denna instans är inaktiverad.
    /// </summary>
    /// <värde>
    /// <c>sant</c> om denna instans är inaktiverad; annars, <c>false</c>.
    /// </värde>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Hämtar eller ställer in ett värde som indikerar om denna instans inte är länkad.
    /// </summary>
    /// <värde>
    /// <c>sant</c> om denna instans inte är länkad; annars, <c>false</c>.
    /// </värde>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Hämtar eller ställer in ett värde som anger om denna instans är inverterad.
    /// </summary>
    /// <värde>
    /// <c>sant</c> om denna instans är inverterad; annars, <c>false</c>.
    /// </värde>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Initierar ett värde baserat på indata <see cref="VectorPathDataResource"/> resurs.
    /// </summary>
    /// <param name="resource">Vektorsökvägens dataresurs.</param>
    /// <param name="imageSize">Bildstorleken för att korrigera konverteringspunktskoordinater.</param>
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

### Se även

* class [VmskResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* hopsättning [Aspose.PSD](../../../)


