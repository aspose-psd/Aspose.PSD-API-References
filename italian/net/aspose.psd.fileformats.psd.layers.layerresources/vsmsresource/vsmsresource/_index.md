---
title: VsmsResource.VsmsResource
second_title: Aspose.PSD per riferimento API .NET
description: VsmsResource costruttore. Inizializza una nuova istanza diVsmsResource classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/vsmsresource/
---
## VsmsResource(byte[]) {#constructor_1}

Inizializza una nuova istanza di[`VsmsResource`](../) classe.

```csharp
public VsmsResource(byte[] data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | Byte[] | I dati della risorsa. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Valore della risorsa Vsms non valido |

### Guarda anche

* class [VsmsResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vsmsresource/)
* assemblea [Aspose.PSD](../../../)

---

## VsmsResource() {#constructor}

Inizializza una nuova istanza di[`VsmsResource`](../) classe.

```csharp
public VsmsResource()
```

### Esempi

L'esempio di codice seguente fornisce le classi per manipolare gli oggetti del percorso vettoriale e illustra come utilizzare tali classi.

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
/// La classe che fornisce lavoro tra <see cref="Layer"/> e <vedere cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Crea il <see cref="VectorPath"/> istanza basata sulle risorse dal livello di input.
    /// </summary>
    /// <param name="psdLayer">Il livello psd.</param>
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
    /// Aggiorna le risorse del livello di input da <see cref="VectorPath"/> istanza o sostituirla con una nuova risorsa di percorso e aggiornamenti.
    /// </summary>
    /// <param name="psdLayer">Il livello psd.</param>
    /// <param name="vectorPath">Il percorso del vettore.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
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
    /// Rimuove i dati del percorso vettoriale dal livello di input.
    /// </summary>
    /// <param name="psdLayer">Il livello psd.</param>
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
    /// Aggiorna i dati delle risorse da <see cref="VectorPath"/> esempio.
    /// </summary>
    /// <param name="pathResource">La risorsa del percorso.</param>
    /// <param name="vogkResource">La risorsa dati di origine del vettore.</param>
    /// <param name="socoResource">La risorsa a tinta unita.</param>
    /// <param name="vectorPath">Il percorso del vettore.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
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
    /// Sostituisce le risorse nel livello con nuove o aggiornate.
    /// </summary>
    /// <param name="psdLayer">Il livello psd.</param>
    /// <param name="pathResource">La risorsa del percorso.</param>
    /// <param name="vogkResource">La risorsa dati di origine del vettore.</param>
    /// <param name="socoResource">La risorsa a tinta unita.</param>
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
    /// Trova <see cref="VectorPathDataResource"/> risorsa nelle risorse del livello di input.
    /// </summary>
    /// <param name="psdLayer">Il livello psd.</param>
    /// <param name="createIfNotExist">Se la risorsa non esiste, per <vedere cref="true"/> crea una nuova risorsa, altrimenti restituisce <see cref="null"/>.</param>
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
    /// Trova <see cref="VogkResource"/> risorsa nelle risorse del livello di input.
    /// </summary>
    /// <param name="psdLayer">Il livello psd.</param>
    /// <param name="createIfNotExist">Se la risorsa non esiste, per <vedere cref="true"/> crea una nuova risorsa, altrimenti restituisce <see cref="null"/>.</param>
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
    /// Trova <see cref="SoCoResource"/> risorsa nelle risorse del livello di input.
    /// </summary>
    /// <param name="psdLayer">Il livello psd.</param>
    /// <param name="createIfNotExist">Se la risorsa non esiste, per <vedere cref="true"/> crea una nuova risorsa, altrimenti restituisce <see cref="null"/>.</param>
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
    /// Convalida il layer con cui lavorare <see cref="VectorDataProvider"/> classe.
    /// </summary>
    /// <param name="livello"></param>
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
/// Il nodo della curva di Bezier, contiene un punto di ancoraggio e due punti di controllo.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Rapporto tra immagine e punto del percorso.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Inizializza una nuova istanza di <see cref="BezierKnot" /> classe.
    /// </summary>
    /// <param name="anchorPoint">Il punto di ancoraggio.</param>
    /// <param name="controlPoint1">Il primo punto di controllo.</param>
    /// <param name="controlPoint2">Il secondo punto di controllo.</param>
    /// <param name="isLinked">Il valore che indica se questo nodo è collegato.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Inizializza una nuova istanza di <see cref="BezierKnot" /> classe basata su <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">Il <see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Inizializza una nuova istanza di <see cref="BezierKnot" /> classe.
    /// </summary>
    /// <param name="anchorPoint">Il punto da utilizzare come punto di ancoraggio e di controllo.</param>
    /// <param name="isLinked">Il valore che indica se questo nodo è collegato.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Ottiene o imposta un valore che indica se questa istanza è collegata.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Ottiene o imposta il primo punto di controllo.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Ottiene o imposta il punto di ancoraggio.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Ottiene o imposta il secondo punto di controllo.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Crea l'istanza di <see cref="BezierKnotRecord"/> sulla base di questa istanza.
    /// </summary>
    /// <param name="isClosed">Indica se questo nodo è chiuso.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
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
    /// Sposta i punti di questo nodo in base ai valori di input.
    /// </summary>
    /// <param name="xOffset">L'offset x.</param>
    /// <param name="yOffset">L'offset y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Converte i valori in punti da risorsa a normale.
    /// </summary>
    /// <param name="point">Il punto con i valori dalla risorsa.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Converte i normali valori punto in punto risorsa.
    /// </summary>
    /// <param name="point">Il punto.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// La figura dai nodi della curva di Bezier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Inizializza una nuova istanza di <see cref="PathShape" /> classe.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Inizializza una nuova istanza di <see cref="PathShape" /> basata su <see cref="VectorPathRecord"/>.
    /// </summary>
    /// <param name="lengthRecord">Il record di lunghezza.</param>
    /// <param name="bezierKnotRecords">I record del nodo bezier.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Ottiene o imposta un valore che indica se questa istanza è chiusa.
    /// </summary>
    /// <valore>
    /// <c>vero</c> se questa istanza è chiusa; in caso contrario, <c>false</c>.
    /// </valore>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Ottiene o imposta le operazioni sul percorso (operazioni booleane).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Ottiene o imposta l'indice della forma del percorso corrente nel livello.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Ottiene i punti della curva di Bezier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Crea il <see cref="VectorPathRecord"/> record basati su questa istanza.
    /// </summary>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
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
    /// Inizializza un valore in base ai record di input.
    /// </summary>
    /// <param name="bezierKnotRecords">I record del nodo bezier.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
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
/// La classe che contiene i percorsi vettoriali.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Inizializza una nuova istanza di <see cref="VectorPath" /> basata su <see cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">La risorsa di dati del percorso vettoriale.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Ottiene o imposta un valore che indica se il riempimento inizia con tutti i pixel.
    /// </summary>
    /// <valore>
    /// Il riempimento inizia con tutti i pixel.
    /// </valore>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Ottiene le forme vettoriali.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Ottiene o imposta il colore di riempimento del tracciato vettoriale.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Ottiene o imposta la versione.
    /// </summary>
    /// <valore>
    /// La versione.
    /// </valore>
    public int Version { get; set; }

    /// <summary>
    /// Ottiene o imposta un valore che indica se questa istanza è disabilitata.
    /// </summary>
    /// <valore>
    /// <c>vero</c> se questa istanza è disabilitata; in caso contrario, <c>false</c>.
    /// </valore>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Ottiene o imposta un valore che indica se questa istanza non è collegata.
    /// </summary>
    /// <valore>
    /// <c>vero</c> se questa istanza non è collegata; in caso contrario, <c>false</c>.
    /// </valore>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Ottiene o imposta un valore che indica se questa istanza è invertita.
    /// </summary>
    /// <valore>
    /// <c>vero</c> se questa istanza è invertita; in caso contrario, <c>false</c>.
    /// </valore>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Inizializza un valore in base all'input <see cref="VectorPathDataResource"/> risorsa.
    /// </summary>
    /// <param name="resource">La risorsa di dati del percorso vettoriale.</param>
    /// <param name="imageSize">La dimensione dell'immagine per correggere le coordinate del punto di conversione.</param>
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

### Guarda anche

* class [VsmsResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vsmsresource/)
* assemblea [Aspose.PSD](../../../)


