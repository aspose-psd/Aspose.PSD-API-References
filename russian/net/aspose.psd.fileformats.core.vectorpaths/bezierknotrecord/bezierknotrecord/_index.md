---
title: BezierKnotRecord
second_title: Справочник по Aspose.PSD для .NET API
description: Инициализирует новый экземпляр классаBezierKnotRecordaspose.psd.fileformats.core.vectorpaths/bezierknotrecord.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/bezierknotrecord/
---
## BezierKnotRecord() {#constructor}

Инициализирует новый экземпляр класса[`BezierKnotRecord`](../../bezierknotrecord).

```csharp
public BezierKnotRecord()
```

### Примеры

В следующем примере кода представлены классы для управления объектами векторного пути и показано, как использовать эти классы.

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
/// Класс, обеспечивающий работу между <see cref="Layer"/> и <см. cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// Создает <see cref="VectorPath"/> экземпляр на основе ресурсов из входного слоя.
    /// </summary>
    /// <param name="psdLayer">Слой PSD.</param>
    /// <возвращает><see cref="VectorPath"/> экземпляр на основе ресурсов из входного слоя.</returns>
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
    /// Обновляет ресурсы входного слоя из <see cref="VectorPath"/> экземпляр или заменить новым ресурсом пути и обновлениями.
    /// </summary>
    /// <param name="psdLayer">Слой PSD.</param>
    /// <param name="vectorPath">Векторный путь.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
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
    /// Удаляет данные векторного пути из входного слоя.
    /// </summary>
    /// <param name="psdLayer">Слой PSD.</param>
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
    /// Обновляет данные о ресурсах из <see cref="VectorPath"/> пример.
    /// </summary>
    /// <param name="pathResource">Ресурс пути.</param>
    /// <param name="vogkResource">Ресурс исходных данных вектора.</param>
    /// <param name="socoResource">Ресурс сплошного цвета.</param>
    /// <param name="vectorPath">Векторный путь.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
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
    /// Заменяет ресурсы в слое обновленными или новыми.
    /// </summary>
    /// <param name="psdLayer">Слой PSD.</param>
    /// <param name="pathResource">Ресурс пути.</param>
    /// <param name="vogkResource">Ресурс исходных данных вектора.</param>
    /// <param name="socoResource">Ресурс сплошного цвета.</param>
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
    /// Находит <see cref="VectorPathDataResource"/> ресурс в ресурсах входного слоя.
    /// </summary>
    /// <param name="psdLayer">Слой PSD.</param>
    /// <param name="createIfNotExist">Если ресурс не существует, то для <see cref="true"/> создает новый ресурс, в противном случае возвращает <see cref="null"/>.</param>
    /// <returns><see cref="VectorPathDataResource"/> ресурс.</returns>
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
    /// Находит <see cref="VogkResource"/> ресурс в ресурсах входного слоя.
    /// </summary>
    /// <param name="psdLayer">Слой PSD.</param>
    /// <param name="createIfNotExist">Если ресурс не существует, то для <see cref="true"/> создает новый ресурс, в противном случае возвращает <see cref="null"/>.</param>
    /// <returns><see cref="VogkResource"/> ресурс.</returns>
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
    /// Находит <see cref="SoCoResource"/> ресурс в ресурсах входного слоя.
    /// </summary>
    /// <param name="psdLayer">Слой PSD.</param>
    /// <param name="createIfNotExist">Если ресурс не существует, то для <see cref="true"/> создает новый ресурс, в противном случае возвращает <see cref="null"/>.</param>
    /// <returns><see cref="SoCoResource"/> ресурс.</returns>
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
    /// Проверка слоя для работы с ним <see cref="VectorDataProvider"/> учебный класс.
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
/// Узел кривой Безье, он содержит одну опорную точку и две контрольные точки.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// Отношение изображения к точке пути.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// Инициализирует новый экземпляр <see cref="BezierKnot" /> учебный класс.
    /// </summary>
    /// <param name="anchorPoint">Точка привязки.</param>
    /// <param name="controlPoint1">Первая контрольная точка.</param>
    /// <param name="controlPoint2">Вторая контрольная точка.</param>
    /// <param name="isLinked">Значение, указывающее, связан ли этот узел.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// Инициализирует новый экземпляр <see cref="BezierKnot" /> класс на основе <see cref="BezierKnotRecord"/>.
    /// </summary>
    /// <param name="bezierKnotRecord"><see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// Инициализирует новый экземпляр <see cref="BezierKnot" /> учебный класс.
    /// </summary>
    /// <param name="anchorPoint">Точка привязки и контрольные точки.</param>
    /// <param name="isLinked">Значение, указывающее, связан ли этот узел.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// Получает или устанавливает значение, указывающее, связан ли этот экземпляр.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// Получает или устанавливает первую контрольную точку.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// Получает или устанавливает точку привязки.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// Получает или устанавливает вторую контрольную точку.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// Создает экземпляр <see cref="BezierKnotRecord"/> на базе этого экземпляра.
    /// </summary>
    /// <param name="isClosed">Указывает, находится ли этот узел в закрытой форме.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
    /// <returns>Экземпляр <see cref="BezierKnotRecord"/> на основе этого экземпляра.</returns>
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
    /// Сдвигает точки узла на входные значения.
    /// </summary>
    /// <param name="xOffset">Смещение по оси x.</param>
    /// <param name="yOffset">Смещение по оси Y.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// Преобразует значения точек из ресурсных в нормальные.
    /// </summary>
    /// <param name="point">Точка со значениями из ресурса.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
    /// <returns>Точка, преобразованная в нормальную.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// Преобразует обычные значения точек в ресурсные точки.
    /// </summary>
    /// <param name="point">Точка.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
    /// <returns>Точка со значениями для ресурса.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Фигура из узлов кривой Безье.
/// </summary>
public class PathShape
{
    /// <summary>
    /// Инициализирует новый экземпляр <see cref="PathShape" /> учебный класс.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// Инициализирует новый экземпляр <see cref="PathShape" /> на основе <see cref="VectorPathRecord"/>.
    /// </summary>
    /// <param name="lengthRecord">Запись длины.</param>
    /// <param name="bezierKnotRecords">Записи узла Безье.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// Получает или устанавливает значение, указывающее, закрыт ли этот экземпляр.
    /// </summary>
    /// <значение>
    /// <c>true</c> если этот экземпляр закрыт; в противном случае <c>false</c>.
    /// </значение>
    public bool IsClosed { get; set; }

    /// <summary>
    /// Получает или устанавливает операции пути (логические операции).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// Получает или устанавливает индекс текущей формы пути в слое.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Получает точки кривой Безье.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// Создает <see cref="VectorPathRecord"/> записи на основе этого экземпляра.
    /// </summary>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
    /// <returns>Возвращает один <see cref="LengthRecord"/> и <см. cref="BezierKnotRecord"/> для каждой точки в этом экземпляре.</returns>
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
    /// Инициализирует значения на основе входных записей.
    /// </summary>
    /// <param name="bezierKnotRecords">Записи узла Безье.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
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
/// Класс, содержащий векторные пути.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// Инициализирует новый экземпляр <see cref="VectorPath" /> класс на основе <see cref="VectorPathDataResource"/>.
    /// </summary>
    /// <param name="vectorPathDataResource">Ресурс данных векторного пути.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// Получает или задает значение, указывающее, начинается ли заполнение со всех пикселей.
    /// </summary>
    /// <значение>
    /// Заливка начинается со всех пикселей.
    /// </значение>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// Получает векторные фигуры.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// Получает или задает цвет заливки векторного пути.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// Получает или устанавливает версию.
    /// </summary>
    /// <значение>
    /// Версия.
    /// </значение>
    public int Version { get; set; }

    /// <summary>
    /// Получает или задает значение, указывающее, отключен ли этот экземпляр.
    /// </summary>
    /// <значение>
    /// <c>true</c> если этот экземпляр отключен; в противном случае <c>false</c>.
    /// </значение>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// Получает или задает значение, указывающее, не связан ли этот экземпляр.
    /// </summary>
    /// <значение>
    /// <c>true</c> если этот экземпляр не связан; в противном случае <c>false</c>.
    /// </значение>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// Получает или задает значение, указывающее, инвертирован ли этот экземпляр.
    /// </summary>
    /// <значение>
    /// <c>true</c> если этот экземпляр инвертирован; в противном случае <c>false</c>.
    /// </значение>
    public bool IsInverted { get; set; }

    /// <summary>
    /// Инициализирует значения на основе ввода <see cref="VectorPathDataResource"/> ресурс.
    /// </summary>
    /// <param name="resource">Ресурс данных векторного пути.</param>
    /// <param name="imageSize">Размер изображения для корректного преобразования координат точки.</param>
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

### Смотрите также

* class [BezierKnotRecord](../../bezierknotrecord)
* пространство имен [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord)
* сборка [Aspose.PSD](../../../)

---

## BezierKnotRecord(byte[]) {#constructor_1}

Инициализирует новый экземпляр класса[`BezierKnotRecord`](../../bezierknotrecord).

```csharp
public BezierKnotRecord(byte[] data)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | Byte[] | Данные записи. |

### Смотрите также

* class [BezierKnotRecord](../../bezierknotrecord)
* пространство имен [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
