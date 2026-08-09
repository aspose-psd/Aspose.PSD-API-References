---
title: "VsmsResource.VsmsResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "VsmsResource-Konstruktor. Initialisiert eine neue Instanz der VsmsResource-Klasse"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/vsmsresource/
---
{{< psd/tize >}}
## VsmsResource(byte[]) {#constructor_1}

Initialisiert eine neue Instanz der [`VsmsResource`](../)-Klasse.

```csharp
public VsmsResource(byte[] data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | Byte[] | Die Ressourcendaten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Ungültiger Vsms Resource-Wert |

### Siehe auch

* class [VsmsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## VsmsResource() {#constructor}

Initialisiert eine neue Instanz der [`VsmsResource`](../)-Klasse.

```csharp
public VsmsResource()
```

## Beispiele

Das folgende Codebeispiel stellt Klassen zum Manipulieren von Vektorpfadobjekten bereit und zeigt, wie diese Klassen verwendet werden.

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
/// Die Klasse, die die Arbeit zwischen <see cref=\"Layer\"/> und <see cref=\"VectorPath\"/> bereitstellt.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Erstellt die <see cref=\"VectorPath\"/>-Instanz basierend auf Ressourcen aus dem Eingabelayer.
    /// </summary>
    /// <param name=\"psdLayer\">Der PSD-Layer.</param>
    /// <returns>die <see cref=\"VectorPath\"/>-Instanz basierend auf Ressourcen aus dem Eingabelayer.</returns>
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
    /// Aktualisiert die Ressourcen des Eingabelayers aus der <see cref=\"VectorPath\"/>-Instanz oder ersetzt sie durch eine neue Pfadressource und aktualisiert sie.
    /// </summary>
    /// <param name=\"psdLayer\">Der PSD-Layer.</param>
    /// <param name=\"vectorPath\">Der Vektorpfad.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
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
    /// Entfernt die Vektorpfaddaten aus dem Eingabelayer.
    /// </summary>
    /// <param name=\"psdLayer\">Der PSD-Layer.</param>
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
    /// Aktualisiert die Ressourcendaten aus der <see cref=\"VectorPath\"/>-Instanz.
    /// </summary>
    /// <param name=\"pathResource\">Die Pfadressource.</param>
    /// <param name=\"vogkResource\">Die Vektor-Ursprungsdatenressource.</param>
    /// <param name=\"socoResource\">Die Ressource für Vollfarbe.</param>
    /// <param name=\"vectorPath\">Der Vektorpfad.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
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
    /// Ersetzt Ressourcen im Layer durch aktualisierte oder neue.
    /// </summary>
    /// <param name=\"psdLayer\">Der PSD-Layer.</param>
    /// <param name=\"pathResource\">Die Pfadressource.</param>
    /// <param name=\"vogkResource\">Die Vektor-Ursprungsdatenressource.</param>
    /// <param name=\"socoResource\">Die Ressource für Vollfarbe.</param>
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
    /// Findet die <see cref=\"VectorPathDataResource\"/> Ressource in den Eingabe‑Layer‑Ressourcen.
    /// </summary>
    /// <param name=\"psdLayer\">Der PSD-Layer.</param>
    /// <param name=\"createIfNotExist\">Wenn die Ressource nicht existiert, dann für <see cref=\"true\"/> wird eine neue Ressource erstellt, andernfalls wird <see cref=\"null\"/> zurückgegeben.</param>
    /// <returns>Die <see cref=\"VectorPathDataResource\"/> Ressource.</returns>
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
    /// Findet die <see cref=\"VogkResource\"/> Ressource in den Eingabe‑Layer‑Ressourcen.
    /// </summary>
    /// <param name=\"psdLayer\">Der PSD-Layer.</param>
    /// <param name=\"createIfNotExist\">Wenn die Ressource nicht existiert, dann für <see cref=\"true\"/> wird eine neue Ressource erstellt, andernfalls wird <see cref=\"null\"/> zurückgegeben.</param>
    /// <returns>Die <see cref=\"VogkResource\"/> Ressource.</returns>
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
    /// Findet die <see cref=\"SoCoResource\"/> Ressource in den Eingabe‑Layer‑Ressourcen.
    /// </summary>
    /// <param name=\"psdLayer\">Der PSD-Layer.</param>
    /// <param name=\"createIfNotExist\">Wenn die Ressource nicht existiert, dann für <see cref=\"true\"/> wird eine neue Ressource erstellt, andernfalls wird <see cref=\"null\"/> zurückgegeben.</param>
    /// <returns>Die <see cref=\"SoCoResource\"/> Ressource.</returns>
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
    /// Validiert das Layer, um mit der Klasse <see cref=\"VectorDataProvider\"/> zu arbeiten.
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
/// Der Bezier‑Kurvenknoten, er enthält einen Ankerpunkt und zwei Steuerpunkte.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Bild‑zu‑Pfad‑Punkt‑Verhältnis.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Initialisiert eine neue Instanz der Klasse <see cref=\"BezierKnot\" />.
    /// </summary>
    /// <param name=\"anchorPoint\">Der Ankerpunkt.</param>
    /// <param name=\"controlPoint1\">Der erste Steuerpunkt.</param>
    /// <param name=\"controlPoint2\">Der zweite Steuerpunkt.</param>
    /// <param name=\"isLinked\">Der Wert, der angibt, ob dieser Knoten verknüpft ist.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Initialisiert eine neue Instanz der Klasse <see cref=\"BezierKnot\" /> basierend auf <see cref=\"BezierKnotRecord\"/>.
    /// </summary>
    /// <param name=\"bezierKnotRecord\">Die <see cref=\"BezierKnotRecord\"/>.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Initialisiert eine neue Instanz der Klasse <see cref=\"BezierKnot\" />.
    /// </summary>
    /// <param name=\"anchorPoint\">Der Punkt, der Anker‑ und Steuerpunkt sein soll.</param>
    /// <param name=\"isLinked\">Der Wert, der angibt, ob dieser Knoten verknüpft ist.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz verknüpft ist.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Ruft den ersten Steuerpunkt ab oder legt ihn fest.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Ruft den Ankerpunkt ab oder legt ihn fest.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Ruft den zweiten Steuerpunkt ab oder legt ihn fest.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Erstellt die Instanz von <see cref=\"BezierKnotRecord\"/> basierend auf dieser Instanz.
    /// </summary>
    /// <param name=\"isClosed\">Gibt an, ob dieser Knoten eine geschlossene Form hat.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
    /// <returns>Die Instanz von <see cref=\"BezierKnotRecord\"/> basierend auf dieser Instanz.</returns>
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
    /// Verschiebt die Punkte dieses Knotens um die Eingabewerte.
    /// </summary>
    /// <param name=\"xOffset\">Der x‑Versatz.</param>
    /// <param name=\"yOffset\">Der y‑Versatz.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Konvertiert Punktwerte von der Ressource in Normalwerte.
    /// </summary>
    /// <param name=\"point\">Der Punkt mit Werten aus der Ressource.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
    /// <returns>Der in Normalwerte konvertierte Punkt.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Konvertiert normale Punktwerte in einen Ressourcpunkt.
    /// </summary>
    /// <param name=\"point\">Der Punkt.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
    /// <returns>Der Punkt mit Werten für die Ressource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Die Figur aus den Knoten der Bézier‑Kurve.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Initialisiert eine neue Instanz der Klasse <see cref=\"PathShape\" />.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Initialisiert eine neue Instanz der Klasse <see cref=\"PathShape\" /> basierend auf <see cref=\"VectorPathRecord\"/>.
    /// </summary>
    /// <param name=\"lengthRecord\">Der Längendatensatz.</param>
    /// <param name=\"bezierKnotRecords\">Die Bezier‑Knoten‑Datensätze.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz geschlossen ist.
    /// </summary>
    /// <value>
    ///   <c>true</c> wenn diese Instanz geschlossen ist; andernfalls <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Ruft die Pfadoperationen (Boolesche Operationen) ab oder legt sie fest.
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Ruft den Index der aktuellen Pfadform in der Ebene ab oder legt ihn fest.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Ruft die Punkte der Bézier‑Kurve ab.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Erstellt die <see cref=\"VectorPathRecord\"/>‑Datensätze basierend auf dieser Instanz.
    /// </summary>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
    /// <returns>Gibt für jeden Punkt in dieser Instanz ein <see cref=\"LengthRecord\"/> und ein <see cref=\"BezierKnotRecord\"/> zurück.</returns>
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
    /// Initialisiert Werte basierend auf Eingabedatensätzen.
    /// </summary>
    /// <param name=\"bezierKnotRecords\">Die Bezier‑Knoten‑Datensätze.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
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
/// Die Klasse, die Vektorpfade enthält.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Initialisiert eine neue Instanz der <see cref=\"VectorPath\" /> Klasse basierend auf <see cref=\"VectorPathDataResource\"/>.
    /// </summary>
    /// <param name=\"vectorPathDataResource\">Die Vektorpfad-Datenressource.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Füllung mit allen Pixeln beginnt.
    /// </summary>
    /// <value>
    /// Die Füllung beginnt mit allen Pixeln.
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Ruft die Vektorformen ab.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Ruft die Füllfarbe des Vektorpfads ab oder legt sie fest.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Ruft die Version ab oder legt sie fest.
    /// </summary>
    /// <value>
    /// Die Version.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz deaktiviert ist.
    /// </summary>
    /// <value>
    ///   <c>true</c> wenn diese Instanz deaktiviert ist; andernfalls <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz nicht verknüpft ist.
    /// </summary>
    /// <value>
    ///   <c>true</c> wenn diese Instanz nicht verknüpft ist; andernfalls <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz invertiert ist.
    /// </summary>
    /// <value>
    ///   <c>true</c> wenn diese Instanz invertiert ist; andernfalls <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Initialisiert Werte basierend auf der Eingabe-<see cref=\"VectorPathDataResource\"/> Ressource.
    /// </summary>
    /// <param name=\"resource\">Die Vektorpfad-Datenressource.</param>
    /// <param name=\"imageSize\">Die Bildgröße zur Korrektur der Umwandlung von Punktkoordinaten.</param>
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

### Siehe auch

* class [VsmsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


