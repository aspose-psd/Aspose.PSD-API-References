---
title: VmskResource.VmskResource
second_title: Aspose.PSD for .NET API 参考
description: VmskResource 构造函数. 初始化一个新的实例VmskResource类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
## VmskResource(byte[]) {#constructor_1}

初始化一个新的实例[`VmskResource`](../)类.

```csharp
public VmskResource(byte[] data)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| data | Byte[] | 资源数据。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 无效的 Vmsk 资源值 |

### 也可以看看

* class [VmskResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* 部件 [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

初始化一个新的实例[`VmskResource`](../)类.

```csharp
public VmskResource()
```

### 例子

以下代码示例提供了用于操作矢量路径对象的类，并演示了如何使用这些类。

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
/// 在 <see cref="Layer"/> 之间提供工作的类和 <参见 cref="VectorPath"/>。
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// 创建 <see cref="VectorPath"/>基于输入层资源的实例。
    /// </summary>
    /// <param name="psdLayer">psd层。</param>
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
    /// 从 <see cref="VectorPath"/> 更新输入层资源实例，或替换为新的路径资源和更新。
    /// </summary>
    /// <param name="psdLayer">psd层。</param>
    /// <param name="vectorPath">矢量路径。</param>
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
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
    /// 从输入层移除矢量路径数据。
    /// </summary>
    /// <param name="psdLayer">psd层。</param>
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
    /// 从 <see cref="VectorPath"/> 更新资源数据实例。
    /// </summary>
    /// <param name="pathResource">路径资源。</param>
    /// <param name="vogkResource">矢量源数据资源。</param>;
    /// <param name="socoResource">纯色资源。</param>
    /// <param name="vectorPath">矢量路径。</param>
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
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
    /// 用更新的或新的资源替换图层中的资源。
    /// </summary>
    /// <param name="psdLayer">psd层。</param>
    /// <param name="pathResource">路径资源。</param>
    /// <param name="vogkResource">矢量源数据资源。</param>;
    /// <param name="socoResource">纯色资源。</param>
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
    /// 查找 <see cref="VectorPathDataResource"/>输入层资源中的资源。
    /// </summary>
    /// <param name="psdLayer">psd层。</param>
    /// <param name="createIfNotExist">如果资源不存在，则为 <see cref="true"/>创建一个新资源，否则返回 <see cref="null"/>.</param>
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
    /// 找到 <see cref="VogkResource"/>输入层资源中的资源。
    /// </summary>
    /// <param name="psdLayer">psd层。</param>
    /// <param name="createIfNotExist">如果资源不存在，则为 <see cref="true"/>创建一个新资源，否则返回 <see cref="null"/>.</param>
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
    /// 找到 <see cref="SoCoResource"/>输入层资源中的资源。
    /// </summary>
    /// <param name="psdLayer">psd层。</param>
    /// <param name="createIfNotExist">如果资源不存在，则为 <see cref="true"/>创建一个新资源，否则返回 <see cref="null"/>.</param>
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
    /// 验证图层以使用 <see cref="VectorDataProvider"/>班级。
    /// </summary>
    /// <param name="layer"></param>;
    /// <exception cref="ArgumentNullException"></exception>;
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
/// 贝塞尔曲线结，它包含一个锚点和两个控制点。
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// 图像与路径点的比率。
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// 初始化 <see cref="BezierKnot" /> 的一个新实例班级。
    /// </summary>
    /// <param name="anchorPoint">锚点。</param>
    /// <param name="controlPoint1">第一个控制点。</param>
    /// <param name="controlPoint2">第二个控制点。</param>
    /// <param name="isLinked">该结是否链接的值。</param>;
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// 初始化 <see cref="BezierKnot" /> 的一个新实例基于 <see cref="BezierKnotRecord"/> 的类。
    /// </summary>
    /// <param name="bezierKnotRecord"><see cref="BezierKnotRecord"/>.</param>;
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// 初始化 <see cref="BezierKnot" /> 的一个新实例班级。
    /// </summary>
    /// <param name="anchorPoint">要作为锚点和控制点的点。</param>;
    /// <param name="isLinked">该结是否链接的值。</param>;
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// 获取或设置一个值，该值指示此实例是否已链接。
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// 获取或设置第一个控制点。
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// 获取或设置锚点。
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// 获取或设置第二个控制点。
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// 创建实例 <see cref="BezierKnotRecord"/>基于这个实例。
    /// </summary>
    /// <param name="isClosed">表示这个结是否是闭合的。</param>;
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
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
    /// 按输入值移动此结点。
    /// </summary>
    /// <param name="xOffset">x 偏移量。</param>
    /// <param name="yOffset">y 偏移量。</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// 将点值从资源转换为正常。
    /// </summary>
    /// <param name="point">具有资源值的点。</param>
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// 将普通点值转换为资源点。
    /// </summary>
    /// <param name="point">点。</param>
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// 来自贝塞尔曲线结的图形。
/// </summary>
public class PathShape
{
    /// <summary>
    /// 初始化 <see cref="PathShape" /> 的新实例班级。
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// 初始化 <see cref="PathShape" /> 的新实例基于 <see cref="VectorPathRecord"/> 的类。
    /// </summary>
    /// <param name="lengthRecord">长度记录。</param>
    /// <param name="bezierKnotRecords">贝塞尔结记录。</param>;
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// 获取或设置一个值，指示此实例是否已关闭。
    /// </summary>
    /// <值>;
    /// <c>真</c>;如果此实例已关闭；否则，<c> 为假</c>。
    /// </值>
    public bool IsClosed { get; set; }

    /// <summary>
    /// 获取或设置路径操作（布尔操作）。
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// 获取或设置图层中当前路径形状的索引。
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// 获取贝塞尔曲线的点。
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// 创建 <see cref="VectorPathRecord"/>基于此实例的记录。
    /// </summary>
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
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
    /// 根据输入记录初始化一个值。
    /// </summary>
    /// <param name="bezierKnotRecords">贝塞尔结记录。</param>;
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
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
/// 包含矢量路径的类。
/// </summary>
public class VectorPath
{
    /// <summary>
    /// 初始化 <see cref="VectorPath" /> 的新实例基于 <see cref="VectorPathDataResource"/> 的类。
    /// </summary>
    /// <param name="vectorPathDataResource">矢量路径数据资源。</param>;
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// 获取或设置一个值，该值指示填充是否从所有像素开始。
    /// </summary>
    /// <值>;
    /// is fill 从所有像素开始。
    /// </值>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// 获取矢量形状。
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// 获取或设置矢量路径填充颜色。
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// 获取或设置版本。
    /// </summary>
    /// <值>;
    /// 版本。
    /// </值>
    public int Version { get; set; }

    /// <summary>
    /// 获取或设置一个值，该值指示此实例是否被禁用。
    /// </summary>
    /// <值>;
    /// <c>真</c>;如果此实例被禁用；否则，<c> 为假</c>。
    /// </值>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// 获取或设置一个值，该值指示此实例是否未链接。
    /// </summary>
    /// <值>;
    /// <c>真</c>;如果此实例未链接；否则，<c> 为假</c>。
    /// </值>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// 获取或设置一个值，该值指示此实例是否反转。
    /// </summary>
    /// <值>;
    /// <c>真</c>;如果这个实例是倒置的；否则，<c> 为假</c>。
    /// </值>
    public bool IsInverted { get; set; }

    /// <summary>
    /// 根据输入初始化一个值 <see cref="VectorPathDataResource"/>资源。
    /// </summary>
    /// <param name="resource">向量路径数据资源。</param>
    /// <param name="imageSize">校正转换点坐标的图像大小。</param>;
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

### 也可以看看

* class [VmskResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vmskresource/)
* 部件 [Aspose.PSD](../../../)


