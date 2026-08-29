---
title: "InitialFillRuleRecord.InitialFillRuleRecord"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ InitialFillRuleRecord. يهيئ مثيلاً جديدًا من الفئة InitialFillRuleRecord"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/initialfillrulerecord/initialfillrulerecord/
---
{{< psd/tize >}}
## InitialFillRuleRecord() {#constructor}

يهيئ مثيلاً جديدًا من الفئة [`InitialFillRuleRecord`](../).

```csharp
public InitialFillRuleRecord()
```

### انظر أيضًا

* class [InitialFillRuleRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## InitialFillRuleRecord(bool) {#constructor_1}

يهيئ مثيلاً جديدًا من الفئة [`InitialFillRuleRecord`](../).

```csharp
public InitialFillRuleRecord(bool isFillStartsWithAllPixels)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| isFillStartsWithAllPixels | Boolean | التعبئة تبدأ بجميع البكسلات. |

## أمثلة

مثال الشيفرة التالي يوفر الفئات للتعامل مع كائنات مسار المتجه ويظهر كيفية استخدام تلك الفئات.

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
/// الفئة التي توفر العمل بين <see cref="Layer"/> و <see cref="VectorPath"/>.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// ينشئ مثيل <see cref="VectorPath"/> بناءً على الموارد من الطبقة المدخلة.
    /// </summary>
    /// <param name="psdLayer">طبقة psd.</param>
    /// <returns>مثيل <see cref="VectorPath"/> بناءً على الموارد من الطبقة المدخلة.</returns>
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
    /// يحدّث موارد الطبقة المدخلة من مثيل <see cref="VectorPath"/>، أو يستبدل بموارد مسار جديدة ويحدّث.
    /// </summary>
    /// <param name="psdLayer">طبقة psd.</param>
    /// <param name="vectorPath">مسار المتجه.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
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
    /// يزيل بيانات مسار المتجه من الطبقة المدخلة.
    /// </summary>
    /// <param name="psdLayer">طبقة psd.</param>
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
    /// يحدّث بيانات الموارد من مثيل <see cref="VectorPath"/>.
    /// </summary>
    /// <param name="pathResource">المورد المسار.</param>
    /// <param name="vogkResource">مورد بيانات أصل المتجه.</param>
    /// <param name="socoResource">مورد اللون الصلب.</param>
    /// <param name="vectorPath">مسار المتجه.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
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
    /// يستبدل الموارد في الطبقة بالموارد المحدثة أو الجديدة.
    /// </summary>
    /// <param name="psdLayer">طبقة psd.</param>
    /// <param name="pathResource">المورد المسار.</param>
    /// <param name="vogkResource">مورد بيانات أصل المتجه.</param>
    /// <param name="socoResource">مورد اللون الصلب.</param>
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
    /// يجد المورد <see cref="VectorPathDataResource"/> في موارد الطبقة المدخلة.
    /// </summary>
    /// <param name="psdLayer">طبقة psd.</param>
    /// <param name="createIfNotExist">إذا لم يكن المورد موجوداً، فإن <see cref="true"/> ينشئ مورداً جديداً، وإلا يرجع <see cref="null"/>.</param>
    /// <returns>المورد <see cref="VectorPathDataResource"/>.</returns>
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
    /// يجد المورد <see cref="VogkResource"/> في موارد الطبقة المدخلة.
    /// </summary>
    /// <param name="psdLayer">طبقة psd.</param>
    /// <param name="createIfNotExist">إذا لم يكن المورد موجوداً، فإن <see cref="true"/> ينشئ مورداً جديداً، وإلا يرجع <see cref="null"/>.</param>
    /// <returns>المورد <see cref="VogkResource"/>.</returns>
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
    /// يجد المورد <see cref="SoCoResource"/> في موارد الطبقة المدخلة.
    /// </summary>
    /// <param name="psdLayer">طبقة psd.</param>
    /// <param name="createIfNotExist">إذا لم يكن المورد موجوداً، فإن <see cref="true"/> ينشئ مورداً جديداً، وإلا يرجع <see cref="null"/>.</param>
    /// <returns>المورد <see cref="SoCoResource"/>.</returns>
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
    /// يتحقق من صحة الطبقة للعمل مع الفئة <see cref="VectorDataProvider"/>.
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
/// العقدة في منحنى بيزييه، تحتوي على نقطة ارتكاز واحدة ونقطتي تحكم.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// نسبة الصورة إلى نقطة المسار.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// ينشئ مثيلاً جديدًا للفئة <see cref=\"BezierKnot\" />.
    /// </summary>
    /// <param name=\"anchorPoint\">نقطة الارتكاز.</param>
    /// <param name=\"controlPoint1\">نقطة التحكم الأولى.</param>
    /// <param name=\"controlPoint2\">نقطة التحكم الثانية.</param>
    /// <param name=\"isLinked\">القيمة التي تشير إلى ما إذا كانت هذه العقدة مرتبطة.</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// ينشئ مثيلاً جديدًا للفئة <see cref=\"BezierKnot\" /> بناءً على <see cref=\"BezierKnotRecord\"/>.
    /// </summary>
    /// <param name=\"bezierKnotRecord\">الـ <see cref=\"BezierKnotRecord\"/>.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// ينشئ مثيلاً جديدًا للفئة <see cref=\"BezierKnot\" />.
    /// </summary>
    /// <param name=\"anchorPoint\">النقطة التي تكون نقطة ارتكاز ونقاط تحكم.</param>
    /// <param name=\"isLinked\">القيمة التي تشير إلى ما إذا كانت هذه العقدة مرتبطة.</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مرتبطًا.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// يحصل أو يعيّن نقطة التحكم الأولى.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// يحصل أو يعيّن نقطة الارتكاز.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// يحصل أو يعيّن نقطة التحكم الثانية.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// ينشئ المثيل من <see cref=\"BezierKnotRecord\"/> بناءً على هذا المثيل.
    /// </summary>
    /// <param name=\"isClosed\">يشير إلى ما إذا كانت هذه العقدة في شكل مغلق.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
    /// <returns>المثيل من <see cref=\"BezierKnotRecord\"/> بناءً على هذا المثيل.</returns>
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
    /// ينقل نقاط هذه العقدة بالقيم المدخلة.
    /// </summary>
    /// <param name=\"xOffset\">الإزاحة الأفقية.</param>
    /// <param name=\"yOffset\">الإزاحة العمودية.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// يحوّل قيم النقاط من المورد إلى العادية.
    /// </summary>
    /// <param name=\"point\">النقطة ذات القيم من المورد.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
    /// <returns>النقطة المحوّلة إلى العادية.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// يحول قيم النقاط العادية إلى نقطة المورد.
    /// </summary>
    /// <param name=\"point\">النقطة.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
    /// <returns>النقطة مع القيم للمورد.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// الشكل من عقد منحنى بيزييه.
/// </summary>
public class PathShape
{
    /// <summary>
    /// ينشئ مثيلاً جديدًا من الفئة <see cref=\"PathShape\" />.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// ينشئ مثيلاً جديدًا من الفئة <see cref=\"PathShape\" /> بناءً على <see cref=\"VectorPathRecord\"/>'.
    /// </summary>
    /// <param name=\"lengthRecord\">سجل الطول.</param>
    /// <param name=\"bezierKnotRecords\">سجلات عقد بيزييه.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا.
    /// </summary>
    /// <value>
    ///   <c>true</c> إذا كان هذا المثيل مغلقًا؛ وإلا، <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// يحصل أو يضبط عمليات المسار (عمليات منطقية).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// يحصل أو يضبط فهرس شكل المسار الحالي في الطبقة.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// يحصل على نقاط منحنى بيزييه.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// ينشئ سجلات <see cref=\"VectorPathRecord\"/> بناءً على هذا المثيل.
    /// </summary>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
    /// <returns>يرجع سجل <see cref=\"LengthRecord\"/> واحد و<see cref=\"BezierKnotRecord\"/> لكل نقطة في هذا المثيل.</returns>
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
    /// ينشئ قيمًا بناءً على السجلات المدخلة.
    /// </summary>
    /// <param name=\"bezierKnotRecords\">سجلات عقد بيزييه.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
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
/// الفئة التي تحتوي على مسارات المتجهات.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// ينشئ مثيلاً جديدًا من الفئة <see cref=\"VectorPath\" /> بناءً على <see cref=\"VectorPathDataResource\"/>.
    /// </summary>
    /// <param name=\"vectorPathDataResource\">مورد بيانات مسار المتجه.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// يحصل أو يضبط قيمة تشير إلى ما إذا كانت التعبئة تبدأ بجميع البكسلات.
    /// </summary>
    /// <value>
    /// التعبئة تبدأ بجميع البكسلات.
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// يحصل على أشكال المتجه.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// يحصل أو يضبط لون تعبئة مسار المتجه.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// يحصل على أو يضبط الإصدار.
    /// </summary>
    /// <value>
    /// الإصدار.
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// يحصل على أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن معطلاً.
    /// </summary>
    /// <value>
    ///   <c>true</c> إذا كان هذا الكائن معطلاً؛ وإلا، <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// يحصل على أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن غير مرتبط.
    /// </summary>
    /// <value>
    ///   <c>true</c> إذا كان هذا الكائن غير مرتبط؛ وإلا، <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// يحصل على أو يضبط قيمة تشير إلى ما إذا كان هذا الكائن مقلوبًا.
    /// </summary>
    /// <value>
    ///   <c>true</c> إذا كان هذا الكائن مقلوبًا؛ وإلا، <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// يهيئ القيم بناءً على مورد <see cref="VectorPathDataResource"/> المدخل.
    /// </summary>
    /// <param name="resource">مورد بيانات مسار المتجه.</param>
    /// <param name="imageSize">حجم الصورة لتصحيح تحويل إحداثيات النقاط.</param>
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

### انظر أيضًا

* class [InitialFillRuleRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## InitialFillRuleRecord(byte[]) {#constructor_2}

يهيئ مثيلاً جديدًا من الفئة [`InitialFillRuleRecord`](../).

```csharp
public InitialFillRuleRecord(byte[] data)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | Byte[] | بيانات السجل. |

### انظر أيضًا

* class [InitialFillRuleRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


