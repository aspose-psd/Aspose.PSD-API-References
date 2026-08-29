---
title: "VmskResource.VmskResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor de VmskResource. Inicializa una nueva instancia de la clase VmskResource"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
{{< psd/tize >}}
## VmskResource(byte[]) {#constructor_1}

Inicializa una nueva instancia de la clase [`VmskResource`](../).

```csharp
public VmskResource(byte[] data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | Byte[] | Los datos del recurso. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Valor de recurso Vmsk no válido |

### Ver también

* class [VmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

Inicializa una nueva instancia de la clase [`VmskResource`](../).

```csharp
public VmskResource()
```

## Ejemplos

El siguiente ejemplo de código proporciona clases para manipular los objetos de ruta vectorial y demuestra cómo usar esas clases.

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
/// La clase que proporciona trabajo entre <see cref="Layer"/> y <see cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Crea la instancia <see cref="VectorPath"/> basada en los recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <returns>la instancia <see cref="VectorPath"/> basada en los recursos de la capa de entrada.</returns>
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
    /// Actualiza los recursos de la capa de entrada a partir de la instancia <see cref="VectorPath"/>, o los reemplaza por un nuevo recurso de ruta y los actualiza.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="vectorPath">La ruta vectorial.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
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
    /// Elimina los datos de la ruta vectorial de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
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
    /// Actualiza los datos de recursos a partir de la instancia <see cref="VectorPath"/>.
    /// </summary>
    /// <param name="pathResource">El recurso de ruta.</param>
    /// <param name="vogkResource">El recurso de datos de origen vectorial.</param>
    /// <param name="socoResource">El recurso de color sólido.</param>
    /// <param name="vectorPath">La ruta vectorial.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
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
    /// Reemplaza los recursos en la capa por los actualizados o nuevos.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="pathResource">El recurso de ruta.</param>
    /// <param name="vogkResource">El recurso de datos de origen vectorial.</param>
    /// <param name="socoResource">El recurso de color sólido.</param>
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
    /// Busca el recurso <see cref="VectorPathDataResource"/> en los recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="createIfNotExist">Si el recurso no existe, entonces para <see cref="true"/> crea un nuevo recurso, de lo contrario devuelve <see cref="null"/>.</param>
    /// <returns>El recurso <see cref="VectorPathDataResource"/>.</returns>
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
    /// Busca el recurso <see cref="VogkResource"/> en los recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="createIfNotExist">Si el recurso no existe, entonces para <see cref="true"/> crea un nuevo recurso, de lo contrario devuelve <see cref="null"/>.</param>
    /// <returns>El recurso <see cref="VogkResource"/>.</returns>
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
    /// Busca el recurso <see cref="SoCoResource"/> en los recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="createIfNotExist">Si el recurso no existe, entonces para <see cref="true"/> crea un nuevo recurso, de lo contrario devuelve <see cref="null"/>.</param>
    /// <returns>El recurso <see cref="SoCoResource"/>.</returns>
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
    /// Valida la capa para trabajar con la clase <see cref="VectorDataProvider"/>.
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
/// El nudo de la curva Bezier, contiene un punto de anclaje y dos puntos de control.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Relación de imagen a punto de ruta.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Inicializa una nueva instancia de la clase <see cref="BezierKnot" />.
    /// </summary>
    /// <param name="anchorPoint">El punto de anclaje.</param>
    /// <param name="controlPoint1">El primer punto de control.</param>
    /// <param name="controlPoint2">El segundo punto de control.</param>
    /// <param name="isLinked">El valor que indica si este nudo está enlazado.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Inicializa una nueva instancia de la clase <see cref="BezierKnot" /> basada en <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">El <see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Inicializa una nueva instancia de la clase <see cref="BezierKnot" />.
    /// </summary>
    /// <param name="anchorPoint">El punto que será ancla y punto de control.</param>
    /// <param name="isLinked">El valor que indica si este nudo está enlazado.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia está enlazada.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Obtiene o establece el primer punto de control.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Obtiene o establece el punto de anclaje.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Obtiene o establece el segundo punto de control.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Crea la instancia de <see cref="BezierKnotRecord"/> basada en esta instancia.
    /// </summary>
    /// <param name="isClosed">Indicando si este nudo está en una forma cerrada.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
    /// <returns>La instancia de <see cref="BezierKnotRecord"/> basada en esta instancia.</returns>
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
    /// Desplaza los puntos de este nudo por los valores de entrada.
    /// </summary>
    /// <param name="xOffset">El desplazamiento en x.</param>
    /// <param name="yOffset">El desplazamiento en y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Convierte los valores de punto de recurso a normal.
    /// </summary>
    /// <param name="point">El punto con valores del recurso.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
    /// <returns>El punto convertido a normal.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Convierte valores de punto normales a punto de recurso.
    /// </summary>
    /// <param name="point">El punto.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
    /// <returns>El punto con valores para el recurso.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// La figura de los nudos de la curva Bézier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Inicializa una nueva instancia de la clase <see cref="PathShape" />.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Inicializa una nueva instancia de la clase <see cref="PathShape" /> basada en <see cref="VectorPathRecord"/>.
    /// </summary>
    /// <param name="lengthRecord">El registro de longitud.</param>
    /// <param name="bezierKnotRecords">Los registros de nudos Bézier.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia está cerrada.
    /// </summary>
    /// <value>
    ///   <c>true</c> si esta instancia está cerrada; de lo contrario, <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Obtiene o establece las operaciones de ruta (operaciones booleanas).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Obtiene o establece el índice de la forma de ruta actual en la capa.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Obtiene los puntos de la curva Bézier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Crea los registros <see cref="VectorPathRecord"/> basados en esta instancia.
    /// </summary>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
    /// <returns>Devuelve un <see cref="LengthRecord"/> y un <see cref="BezierKnotRecord"/> por cada punto en esta instancia.</returns>
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
    /// Inicializa valores basados en los registros de entrada.
    /// </summary>
    /// <param name="bezierKnotRecords">Los registros de nudos Bézier.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
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
/// La clase que contiene rutas vectoriales.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Inicializa una nueva instancia de la clase <see cref="VectorPath" /> basada en <see cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">El recurso de datos de ruta vectorial.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Obtiene o establece un valor que indica si el relleno comienza con todos los píxeles.
    /// </summary>
    /// <value>
    /// El relleno comienza con todos los píxeles.
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Obtiene las formas vectoriales.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Obtiene o establece el color de relleno de la ruta vectorial.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Obtiene o establece la versión.
    /// </summary>
    /// <value>
    /// La versión.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia está deshabilitada.
    /// </summary>
    /// <value>
    ///   <c>true</c> si esta instancia está deshabilitada; de lo contrario, <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia no está vinculada.
    /// </summary>
    /// <value>
    ///   <c>true</c> si esta instancia no está vinculada; de lo contrario, <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia está invertida.
    /// </summary>
    /// <value>
    ///   <c>true</c> si esta instancia está invertida; de lo contrario, <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Inicializa valores basados en el recurso de entrada <see cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="resource">El recurso de datos de ruta vectorial.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir la conversión de coordenadas de puntos.</param>
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

### Ver también

* class [VmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


