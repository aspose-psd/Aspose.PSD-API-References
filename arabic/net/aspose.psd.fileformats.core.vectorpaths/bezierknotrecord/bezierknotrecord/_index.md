---
title: BezierKnotRecord.BezierKnotRecord
second_title: Aspose.PSD لمرجع .NET API
description: BezierKnotRecord البناء. يقوم بتهيئة مثيل جديد لملفBezierKnotRecord فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/bezierknotrecord/
---
## BezierKnotRecord() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`BezierKnotRecord`](../) فئة .

```csharp
public BezierKnotRecord()
```

### أمثلة

يوفر مثال الكود التالي فئات للتعامل مع كائنات مسار المتجه ويوضح كيفية استخدام هذه الفئات.

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
/// الفئة التي توفر العمل بين < راجع cref = "Layer" / > و < راجع cref = "VectorPath" / > ;.
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// ينشئ < راجع cref = "VectorPath" / > المثيل على أساس الموارد من طبقة الإدخال.
    /// </summary>
    /// < param name = "psdLayer" > طبقة psd. < / param >
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
    /// يحدّث موارد طبقة الإدخال من < راجع cref = "VectorPath" / > المثال ، أو استبداله بمورد وتحديثات مسار جديد.
    /// </summary>
    /// < param name = "psdLayer" > طبقة psd. < / param >
    /// < param name = "vectorPath" > مسار المتجه. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
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
    /// يزيل بيانات مسار المتجه من طبقة الإدخال.
    /// </summary>
    /// < param name = "psdLayer" > طبقة psd. < / param >
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
    /// يقوم بتحديث بيانات الموارد من < راجع cref = "VectorPath" / > مثال.
    /// </summary>
    /// < param name = "pathResource" > مورد المسار. < / param >
    /// < param name = "vogkResource" > مصدر بيانات إنشاء المتجه. < / param >
    /// < param name = "socoResource" > مورد الألوان الصلبة. < / param >
    /// < param name = "vectorPath" > مسار المتجه. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
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
    /// يستبدل الموارد في الطبقة بمصادر محدثة أو جديدة.
    /// </summary>
    /// < param name = "psdLayer" > طبقة psd. < / param >
    /// < param name = "pathResource" > مورد المسار. < / param >
    /// < param name = "vogkResource" > مصدر بيانات إنشاء المتجه. < / param >
    /// < param name = "socoResource" > مورد الألوان الصلبة. < / param >
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
    /// يبحث عن < راجع cref = "VectorPathDataResource" / > الموارد في موارد طبقة الإدخال.
    /// </summary>
    /// < param name = "psdLayer" > طبقة psd. < / param >
    /// < param name = "createIfNotExist" > إذا لم يكن المورد موجودًا ، فعندئذٍ لـ < راجع cref = "true" / > ينشئ موردًا جديدًا ، وإلا ارجع < see cref = "null" / >. < / param >
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
    /// يبحث عن < راجع cref = "VogkResource" / > الموارد في موارد طبقة الإدخال.
    /// </summary>
    /// < param name = "psdLayer" > طبقة psd. < / param >
    /// < param name = "createIfNotExist" > إذا لم يكن المورد موجودًا ، فعندئذٍ لـ < راجع cref = "true" / > ينشئ موردًا جديدًا ، وإلا ارجع < see cref = "null" / >. < / param >
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
    /// يبحث عن < راجع cref = "SoCoResource" / > الموارد في موارد طبقة الإدخال.
    /// </summary>
    /// < param name = "psdLayer" > طبقة psd. < / param >
    /// < param name = "createIfNotExist" > إذا لم يكن المورد موجودًا ، فعندئذٍ لـ < راجع cref = "true" / > ينشئ موردًا جديدًا ، وإلا ارجع < see cref = "null" / >. < / param >
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
    /// يتحقق من صحة الطبقة للعمل مع < راجع cref = "VectorDataProvider" / > فصل.
    /// </summary>
    /// < param name = "layer" > < / param >
    /// < استثناء cref = "ArgumentNullException" > < / استثناء >
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
/// عقدة منحنى بيزير ، تحتوي على نقطة ربط واحدة ونقطتي تحكم.
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// صورة إلى نسبة نقطة المسار.
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// تهيئة مثيل جديد لـ < see cref = "BezierKnot" / > فصل.
    /// </summary>
    /// < param name = "AnchorPoint" > نقطة الارتساء. < / param >
    /// < param name = "controlPoint1" > أول نقطة تحكم. < / param >
    /// < param name = "controlPoint2" > نقطة التحكم الثانية. < / param >
    /// < param name = "isLinked" > القيمة التي تشير إلى ما إذا كانت هذه العقدة مرتبطة. < / param >
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// تهيئة مثيل جديد لـ < see cref = "BezierKnot" / > فئة على أساس < راجع cref = "BezierKnotRecord" / >.
    /// </summary>
    /// < param name = "bezierKnotRecord" > < راجع cref = "BezierKnotRecord" / >. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// تهيئة مثيل جديد لـ < see cref = "BezierKnot" / > فصل.
    /// </summary>
    /// < param name = "anchorPoint" > النقطة المراد ربطها ونقاط التحكم. < / param >
    /// < param name = "isLinked" > القيمة التي تشير إلى ما إذا كانت هذه العقدة مرتبطة. < / param >
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل مرتبطًا أم لا.
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// الحصول على نقطة التحكم الأولى أو تعيينها.
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// الحصول على نقطة الربط أو تحديدها.
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// الحصول على أو تحديد نقطة التحكم الثانية.
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// ينشئ مثيل < راجع cref = "BezierKnotRecord" / > بناء على هذه الحالة.
    /// </summary>
    /// < param name = "مغلق" > للإشارة إلى ما إذا كانت هذه العقدة في شكل مغلق. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
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
    /// ينقل نقاط العقدة هذه بقيم الإدخال.
    /// </summary>
    /// < param name = "xOffset" > إزاحة x. < / param >
    /// < param name = "yOffset" > إزاحة y. < / param >
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// يحول قيم النقاط من مصدر إلى عادي.
    /// </summary>
    /// < param name = "point" > النقطة التي تحتوي على قيم من المورد. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// يحول قيم النقطة العادية إلى نقطة مورد.
    /// </summary>
    /// < param name = "point" > النقطة. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// الشكل المأخوذ من عقدة منحنى بيزيير.
/// </summary>
public class PathShape
{
    /// <summary>
    /// تهيئة مثيل جديد لـ < راجع cref = "PathShape" / > فصل.
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// تهيئة مثيل جديد لـ < راجع cref = "PathShape" / > فئة تستند إلى < راجع cref = "VectorPathRecord" / >
    /// </summary>
    /// < param name = "lengthRecord" > سجل الطول. < / param >
    /// < param name = "bezierKnotRecords" > سجلات عقدة بيزير. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل مغلقًا.
    /// </summary>
    /// العلامة < قيمة > ;
    /// < c > صحيح < / c > إذا تم إغلاق هذا المثال ; بخلاف ذلك ، < c > false < / c >.
    /// العلامة < / القيمة > ;
    public bool IsClosed { get; set; }

    /// <summary>
    /// الحصول على أو تعيين عمليات المسار (العمليات المنطقية).
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// الحصول على أو تحديد فهرس شكل المسار الحالي في الطبقة.
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// يحصل على نقاط منحنى بيزير.
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// ينشئ < راجع cref = "VectorPathRecord" / > السجلات على أساس هذه الحالة.
    /// </summary>
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
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
    /// يقوم بتهيئة القيم بناءً على سجلات الإدخال.
    /// </summary>
    /// < param name = "bezierKnotRecords" > سجلات عقدة بيزير. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
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
/// الفئة التي تحتوي على مسارات متجهية.
/// </summary>
public class VectorPath
{
    /// <summary>
    /// تهيئة مثيل جديد لـ < راجع cref = "VectorPath" / > فئة تستند إلى < راجع cref = "VectorPathDataResource" / >.
    /// </summary>
    /// < param name = "vectorPathDataResource" > مورد بيانات مسار المتجه. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// الحصول على أو تعيين قيمة تشير إلى ما إذا كان التعبئة تبدأ بكل وحدات البكسل.
    /// </summary>
    /// العلامة < قيمة > ;
    /// يبدأ التعبئة بكل وحدات البكسل.
    /// العلامة < / القيمة > ;
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// يحصل على الأشكال المتجهة.
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// الحصول على لون تعبئة مسار المتجه أو تعيينه.
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// الحصول على الإصدار أو تحديده.
    /// </summary>
    /// العلامة < قيمة > ;
    /// النسخة.
    /// العلامة < / القيمة > ;
    public int Version { get; set; }

    /// <summary>
    /// الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معطلاً.
    /// </summary>
    /// العلامة < قيمة > ;
    /// < c > صحيح < / c > إذا تم تعطيل هذه الحالة ; بخلاف ذلك ، < c > false < / c >.
    /// العلامة < / القيمة > ;
    public bool IsDisabled { get; set; }

    /// <summary>
    /// الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط أم لا.
    /// </summary>
    /// العلامة < قيمة > ;
    /// < c > صحيح < / c > إذا لم يتم ربط هذا المثيل ; بخلاف ذلك ، < c > false < / c >.
    /// العلامة < / القيمة > ;
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل معكوسًا أم لا.
    /// </summary>
    /// العلامة < قيمة > ;
    /// < c > صحيح < / c > إذا تم عكس هذا المثال ; بخلاف ذلك ، < c > false < / c >.
    /// العلامة < / القيمة > ;
    public bool IsInverted { get; set; }

    /// <summary>
    /// يقوم بتهيئة القيم بناءً على الإدخال < راجع cref = "VectorPathDataResource" / >; الموارد.
    /// </summary>
    /// < param name = "Resource" > مورد بيانات مسار المتجه. < / param >
    /// < param name = "imageSize" > حجم الصورة لتصحيح إحداثيات نقطة التحويل. < / param >
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

### أنظر أيضا

* class [BezierKnotRecord](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord/)
* المجسم [Aspose.PSD](../../../)

---

## BezierKnotRecord(byte[]) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`BezierKnotRecord`](../) فئة .

```csharp
public BezierKnotRecord(byte[] data)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| data | Byte[] | بيانات السجل. |

### أنظر أيضا

* class [BezierKnotRecord](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../bezierknotrecord/)
* المجسم [Aspose.PSD](../../../)


