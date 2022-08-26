---
title: BezierKnotRecord
second_title: Referencia de API de Aspose.PSD para .NET
description: Inicializa una nueva instancia delBezierKnotRecordaspose.psd.fileformats.core.vectorpaths/bezierknotrecord clase.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/bezierknotrecord/
---
## BezierKnotRecord() {#constructor}

Inicializa una nueva instancia del[`BezierKnotRecord`](../../bezierknotrecord) clase.

```csharp
public BezierKnotRecord()
```

### Ejemplos

El siguiente ejemplo de código proporciona clases para manipular los objetos de ruta de acceso vectorial y demuestra cómo usar esas clases.

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
/// La clase que proporciona trabajo entre <ver cref="Layer"/> y <ver cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Crea el <ver cref="VectorPath"/> instancia basada en recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
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
    /// Actualiza los recursos de la capa de entrada desde <ver cref="VectorPath"/> instancia, o reemplácelo por un nuevo recurso de ruta y actualizaciones.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="vectorPath">La ruta del vector.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
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
    /// Elimina los datos de la ruta del vector de la capa de entrada.
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
    /// Actualiza los datos de recursos de <see cref="VectorPath"/> instancia.
    /// </summary>
    /// <param name="pathResource">El recurso de ruta.</param>
    /// <param name="vogkResource">El recurso de datos de origen del vector.</param>
    /// <param name="socoResource">El recurso de color sólido.</param>
    /// <param name="vectorPath">La ruta del vector.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
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
    /// Reemplaza los recursos en la capa por otros actualizados o nuevos.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="pathResource">El recurso de ruta.</param>
    /// <param name="vogkResource">El recurso de datos de origen del vector.</param>
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
    /// Encuentra el <ver cref="VectorPathDataResource"/> recurso en los recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="createIfNotExist">Si el recurso no existe, entonces para <ver cref="true"/> crea un nuevo recurso; de lo contrario, devuelve <ver cref="null"/>.</param>
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
    /// Encuentra el <ver cref="VogkResource"/> recurso en los recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="createIfNotExist">Si el recurso no existe, entonces para <ver cref="true"/> crea un nuevo recurso; de lo contrario, devuelve <ver cref="null"/>.</param>
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
    /// Encuentra el <ver cref="SoCoResource"/> recurso en los recursos de la capa de entrada.
    /// </summary>
    /// <param name="psdLayer">La capa psd.</param>
    /// <param name="createIfNotExist">Si el recurso no existe, entonces para <ver cref="true"/> crea un nuevo recurso; de lo contrario, devuelve <ver cref="null"/>.</param>
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
    /// Valida la capa para trabajar con <ver cref="VectorDataProvider"/> clase.
    /// </summary>
    /// <param nombre="capa"></param>
    /// <excepción cref="ArgumentNullException"></excepción>
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
    /// Proporción de imagen a punto de ruta.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Inicializa una nueva instancia de <see cref="BezierKnot" /> clase.
    /// </summary>
    /// <param name="anchorPoint">El punto de anclaje.</param>
    /// <param name="controlPoint1">El primer punto de control.</param>
    /// <param name="controlPoint2">El segundo punto de control.</param>
    /// <param name="isLinked">El valor que indica si este nudo está vinculado.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Inicializa una nueva instancia de <see cref="BezierKnot" /> clase basada en <ver cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord">El <ver cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Inicializa una nueva instancia de <see cref="BezierKnot" /> clase.
    /// </summary>
    /// <param name="anchorPoint">El punto que será ancla y puntos de control.</param>
    /// <param name="isLinked">El valor que indica si este nudo está vinculado.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia está vinculada.
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
    /// Crea la instancia de <ver cref="BezierKnotRecord"/> basado en esta instancia.
    /// </summary>
    /// <param name="isClosed">Indicando si este nudo está en forma cerrada.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
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
    /// Cambia los puntos de este nudo por valores de entrada.
    /// </summary>
    /// <param name="xOffset">El desplazamiento x.</param>
    /// <param name="yOffset">El desplazamiento y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Convierte valores de puntos de recurso a normal.
    /// </summary>
    /// <param name="punto">El punto con valores del recurso.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Convierte valores de puntos normales en puntos de recursos.
    /// </summary>
    /// <param name="punto">El punto.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// La figura de los nudos de la curva de Bezier.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Inicializa una nueva instancia de <ver cref="PathShape" /> clase.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Inicializa una nueva instancia de <ver cref="PathShape" /> clase basada en <ver cref="VectorPathRecord"/>'s.
    /// </summary>
    /// <param name="lengthRecord">El registro de longitud.</param>
    /// <param name="bezierKnotRecords">Los registros del nudo bezier.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
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
    /// <valor>
    /// <c>verdadero</c> si esta instancia está cerrada; de lo contrario, <c>falso</c>.
    /// </valor>
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
    /// Obtiene los puntos de la curva Bezier.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Crea el <ver cref="VectorPathRecord"/> registros basados en esta instancia.
    /// </summary>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
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
    /// Inicializa valores basados en registros de entrada.
    /// </summary>
    /// <param name="bezierKnotRecords">Los registros del nudo bezier.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
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
    /// Inicializa una nueva instancia de <ver cref="VectorPath" /> clase basada en <ver cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">El recurso de datos de la ruta del vector.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Obtiene o establece un valor que indica si el relleno comienza con todos los píxeles.
    /// </summary>
    /// <valor>
    /// El relleno comienza con todos los píxeles.
    /// </valor>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Obtiene las formas vectoriales.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Obtiene o establece el color de relleno de la ruta del vector.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Obtiene o establece la versión.
    /// </summary>
    /// <valor>
    /// La versión.
    /// </valor>
    public int Version { get; set; }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia está deshabilitada.
    /// </summary>
    /// <valor>
    /// <c>verdadero</c> si esta instancia está deshabilitada; de lo contrario, <c>falso</c>.
    /// </valor>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia no está vinculada.
    /// </summary>
    /// <valor>
    /// <c>verdadero</c> si esta instancia no está vinculada; de lo contrario, <c>falso</c>.
    /// </valor>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Obtiene o establece un valor que indica si esta instancia está invertida.
    /// </summary>
    /// <valor>
    /// <c>verdadero</c> si esta instancia está invertida; de lo contrario, <c>falso</c>.
    /// </valor>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Inicializa valores basados en la entrada <ver cref="VectorPathDataResource"/> recurso.
    /// </summary>
    /// <param name="resource">El recurso de datos de la ruta del vector.</param>
    /// <param name="imageSize">El tamaño de la imagen para corregir las coordenadas del punto de conversión.</param>
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

* class [BezierKnotRecord](../../bezierknotrecord)
* espacio de nombres [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord)
* asamblea [Aspose.PSD](../../../)

---

## BezierKnotRecord(byte[]) {#constructor_1}

Inicializa una nueva instancia del[`BezierKnotRecord`](../../bezierknotrecord) clase.

```csharp
public BezierKnotRecord(byte[] data)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| data | Byte[] | Los datos de registro. |

### Ver también

* class [BezierKnotRecord](../../bezierknotrecord)
* espacio de nombres [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord)
* asamblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
