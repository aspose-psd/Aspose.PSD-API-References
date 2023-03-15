---
title: VsmsResource.VsmsResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VsmsResource नर्मत. क एक नय उदहरण प्ररंभ करत हैVsmsResource वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/vsmsresource/
---
## VsmsResource(byte[]) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`VsmsResource`](../) वर्ग.

```csharp
public VsmsResource(byte[] data)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | Byte[] | संसाधन डेटा। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | अमान्य वीएसएमएस संसाधन मान |

### यह सभी देखें

* class [VsmsResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vsmsresource/)
* सभा [Aspose.PSD](../../../)

---

## VsmsResource() {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`VsmsResource`](../) वर्ग.

```csharp
public VsmsResource()
```

### उदाहरण

निम्नलिखित कोड उदाहरण वेक्टर पथ वस्तुओं में हेरफेर करने के लिए कक्षाएं प्रदान करता है और दर्शाता है कि उन वर्गों का उपयोग कैसे करें।

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
/// वह वर्ग जो <देखें cref="Layer"/> और <cref="VectorPath"/> देखें।
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// <देखें cref="VectorPath"/> इनपुट परत से संसाधनों के आधार पर उदाहरण।
    /// </summary>
    /// <परम नाम="psdLayer">PSD परत.</param>
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
    /// इनपुट परत संसाधनों को <देखें cref="VectorPath"/> उदाहरण, या नए पथ संसाधन और अपडेट द्वारा प्रतिस्थापित करें।
    /// </summary>
    /// <परम नाम="psdLayer">PSD परत.</param>
    /// <param name="vectorPath">सदिश पथ.</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
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
    /// इनपुट लेयर से वेक्टर पाथ डेटा हटाता है।
    /// </summary>
    /// <परम नाम="psdLayer">PSD परत.</param>
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
    /// संसाधन डेटा को <देखें cref="VectorPath"/> उदाहरण।
    /// </summary>
    /// <param name="pathResource">पथ संसाधन.</param>
    /// <param name="vogkResource">वेक्टर उत्पत्ति डेटा संसाधन।</param>
    /// <param name="socoResource">ठोस रंग संसाधन.</param>
    /// <param name="vectorPath">सदिश पथ.</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
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
    /// संसाधनों को अद्यतन या नए द्वारा परत में बदलता है।
    /// </summary>
    /// <परम नाम="psdLayer">PSD परत.</param>
    /// <param name="pathResource">पथ संसाधन.</param>
    /// <param name="vogkResource">वेक्टर उत्पत्ति डेटा संसाधन।</param>
    /// <param name="socoResource">ठोस रंग संसाधन.</param>
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
    /// <देखें cref="VectorPathDataResource"/> इनपुट परत संसाधनों में संसाधन।
    /// </summary>
    /// <परम नाम="psdLayer">PSD परत.</param>
    /// <param name="createIfNotExist">यदि संसाधन मौजूद नहीं है, तो <देखें cref="true"/> एक नया संसाधन बनाता है, अन्यथा वापस लौटें <देखें cref="null"/>.</param>
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
    /// <देखें cref="VogkResource"/> इनपुट परत संसाधनों में संसाधन।
    /// </summary>
    /// <परम नाम="psdLayer">PSD परत.</param>
    /// <param name="createIfNotExist">यदि संसाधन मौजूद नहीं है, तो <देखें cref="true"/> एक नया संसाधन बनाता है, अन्यथा वापस लौटें <देखें cref="null"/>.</param>
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
    /// <देखें cref="SoCoResource"/> इनपुट परत संसाधनों में संसाधन।
    /// </summary>
    /// <परम नाम="psdLayer">PSD परत.</param>
    /// <param name="createIfNotExist">यदि संसाधन मौजूद नहीं है, तो <देखें cref="true"/> एक नया संसाधन बनाता है, अन्यथा वापस लौटें <देखें cref="null"/>.</param>
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
    /// परत को <देखें cref="VectorDataProvider"/> कक्षा।
    /// </summary>
    /// <परम नाम="परत"></परम>
    /// <अपवाद cref="ArgumentNullException"></Exception>
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
/// बेजियर कर्व नॉट, इसमें एक एंकर पॉइंट और दो कंट्रोल पॉइंट होते हैं।
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// पथ बिंदु अनुपात के लिए छवि।
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// <देखें cref="BezierKnot" /> कक्षा।
    /// </summary>
    /// <परम नाम="anchorPoint">एंकर बिंदु.</param>
    /// <param name="controlPoint1">पहला नियंत्रण बिंदु.</param>
    /// <param name="controlPoint2">वह दूसरा नियंत्रण बिंदु.</param>
    /// <param name="isLinked">यह इंगित करने वाला मान कि क्या यह गाँठ जुड़ी हुई है।</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// <देखें cref="BezierKnot" /> वर्ग <देखें cref="BezierKnotRecord"/> पर आधारित है।
    /// </summary>
    /// <param name="bezierKnotRecord">The <see cref="BezierKnotRecord"/>.</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// <देखें cref="BezierKnot" /> कक्षा।
    /// </summary>
    /// <param name="anchorPoint">एंकर होने वाला बिंदु और नियंत्रण बिंदु.</param>
    /// <param name="isLinked">यह इंगित करने वाला मान कि क्या यह गाँठ जुड़ी हुई है।</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि यह उदाहरण जुड़ा हुआ है या नहीं।
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// पहला नियंत्रण बिंदु प्राप्त करें या सेट करें।
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// एंकर पॉइंट प्राप्त या सेट करता है।
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// दूसरा नियंत्रण बिंदु प्राप्त या सेट करता है।
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// <देखें cref="BezierKnotRecord"/> का उदाहरण बनाता है इस उदाहरण के आधार पर।
    /// </summary>
    /// <param name="isClosed">यह इंगित करता है कि क्या यह गाँठ बंद आकार में है।</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
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
    /// इस गाँठ बिंदु को इनपुट मानों से बदलता है।
    /// </summary>
    /// <param name="xOffset">x ऑफ़सेट.</param>
    /// <param name="yOffset">y ऑफ़सेट.</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// बिंदु मानों को संसाधन से सामान्य में परिवर्तित करता है।
    /// </summary>
    /// <परम नाम="बिंदु">संसाधन से मूल्यों के साथ बिंदु।</परम>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
    /// <returns>The converted to normal point.</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// सामान्य बिंदु मानों को संसाधन बिंदु में कनवर्ट करता है।
    /// </summary>
    /// <परम नाम="बिंदु">बिंदु.</परम>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
    /// <returns>The point with values for resource.</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// बेजियर कर्व के नॉट्स से फिगर।
/// </summary>
public class PathShape
{
    /// <summary>
    /// <देखें cref="PathShape" /> कक्षा।
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// <देखें cref="PathShape" /> वर्ग <देखें cref="VectorPathRecord"/> के आधार पर।
    /// </summary>
    /// <param name="lengthRecord">लंबाई का रिकॉर्ड।</param>
    /// <param name="bezierKnotRecords">बेज़ियर नॉट रिकॉर्ड.</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// एक मान प्राप्त या सेट करता है जो इंगित करता है कि यह उदाहरण बंद है या नहीं।
    /// </summary>
    /// <मान>
    /// <c>true</c> अगर यह उदाहरण बंद है; अन्यथा, <c>गलत</c>.
    /// </मान>
    public bool IsClosed { get; set; }

    /// <summary>
    /// पाथ ऑपरेशंस (बूलियन ऑपरेशंस) प्राप्त या सेट करता है।
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// परत में वर्तमान पथ आकार के सूचकांक को प्राप्त या सेट करता है।
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// बेज़ियर वक्र के बिंदु प्राप्त करता है।
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// <देखें cref="VectorPathRecord"/> इस उदाहरण के आधार पर रिकॉर्ड।
    /// </summary>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
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
    /// इनपुट रिकॉर्ड के आधार पर मूल्यों को आरंभ करता है।
    /// </summary>
    /// <param name="bezierKnotRecords">बेज़ियर नॉट रिकॉर्ड.</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
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
/// वह वर्ग जिसमें वेक्टर पथ हैं।
/// </summary>
public class VectorPath
{
    /// <summary>
    /// <देखें cref="VectorPath" /> वर्ग <देखें cref="VectorPathDataResource"/> पर आधारित है।
    /// </summary>
    /// <param name="vectorPathDataResource">वेक्टर पथ डेटा संसाधन.</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// एक मान प्राप्त या सेट करता है जो इंगित करता है कि भरण सभी पिक्सेल से शुरू होता है या नहीं।
    /// </summary>
    /// <मान>
    /// is fill सभी पिक्सेल से शुरू होता है।
    /// </मान>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// वेक्टर आकार प्राप्त करता है।
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// वेक्टर पाथ फिल कलर प्राप्त या सेट करता है।
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// संस्करण प्राप्त या सेट करता है।
    /// </summary>
    /// <मान>
    /// संस्करण।
    /// </मान>
    public int Version { get; set; }

    /// <summary>
    /// एक मान प्राप्त या सेट करता है जो इंगित करता है कि यह उदाहरण अक्षम है या नहीं।
    /// </summary>
    /// <मान>
    /// <c>true</c> अगर यह उदाहरण अक्षम है; अन्यथा, <c>गलत</c>.
    /// </मान>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// यह इंगित करने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण लिंक नहीं है।
    /// </summary>
    /// <मान>
    /// <c>true</c> अगर यह उदाहरण जुड़ा नहीं है; अन्यथा, <c>गलत</c>.
    /// </मान>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि यह उदाहरण उलटा है या नहीं।
    /// </summary>
    /// <मान>
    /// <c>true</c> यदि यह उदाहरण उलटा है; अन्यथा, <c>गलत</c>.
    /// </मान>
    public bool IsInverted { get; set; }

    /// <summary>
    /// इनपुट के आधार पर मूल्यों को प्रारंभ करता है <देखें cref="VectorPathDataResource"/> संसाधन।
    /// </summary>
    /// <परम नाम="संसाधन">वेक्टर पथ डेटा संसाधन।</param>
    /// <param name="imageSize">बदलाव बिंदु निर्देशांकों को सही करने के लिए छवि का आकार।</param>
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

### यह सभी देखें

* class [VsmsResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vsmsresource/)
* सभा [Aspose.PSD](../../../)


