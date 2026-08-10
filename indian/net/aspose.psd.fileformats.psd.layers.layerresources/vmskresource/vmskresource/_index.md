---
title: "VmskResource.VmskResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VmskResource कंस्ट्रक्टर। VmskResource क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/vmskresource/
---
{{< psd/tize >}}
## VmskResource(byte[]) {#constructor_1}

[`VmskResource`](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public VmskResource(byte[] data)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डेटा | Byte[] | संसाधन डेटा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | अमान्य Vmsk रिसोर्स मान |

### देखें भी

* class [VmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## VmskResource() {#constructor}

[`VmskResource`](../) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public VmskResource()
```

## उदाहरण

निम्नलिखित कोड उदाहरण वेक्टर पाथ ऑब्जेक्ट्स को मैनीपुलेट करने के लिए क्लासेस प्रदान करता है और दिखाता है कि इन क्लासेस का उपयोग कैसे किया जाए।

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
/// वह क्लास जो <see cref="Layer"/> और <see cref="VectorPath"/> के बीच कार्य प्रदान करती है।
/// </summary>
public static class VectorDataProvider
{
    /// <summary>
    /// इनपुट लेयर से रिसोर्सेज़ के आधार पर <see cref="VectorPath"/> इंस्टेंस बनाता है।
    /// </summary>
    /// <param name="psdLayer">psd लेयर।</param>
    /// <returns>इनपुट लेयर से रिसोर्सेज़ के आधार पर <see cref="VectorPath"/> इंस्टेंस।</returns>
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
    /// <see cref="VectorPath"/> इंस्टेंस से इनपुट लेयर रिसोर्सेज़ को अपडेट करता है, या नए पाथ रिसोर्स से बदलकर अपडेट करता है।
    /// </summary>
    /// <param name="psdLayer">psd लेयर।</param>
    /// <param name="vectorPath">वेक्टर पाथ।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
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
    /// <param name="psdLayer">psd लेयर।</param>
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
    /// <see cref="VectorPath"/> इंस्टेंस से रिसोर्सेज़ डेटा को अपडेट करता है।
    /// </summary>
    /// <param name="pathResource">पाथ रिसोर्स।</param>
    /// <param name="vogkResource">वेक्टर ओरिजिनेशन डेटा रिसोर्स।</param>
    /// <param name="socoResource">सॉलिड कलर रिसोर्स।</param>
    /// <param name="vectorPath">वेक्टर पाथ।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
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
    /// लेयर में रिसोर्सेज़ को अपडेटेड या नए द्वारा बदलता है।
    /// </summary>
    /// <param name="psdLayer">psd लेयर।</param>
    /// <param name="pathResource">पाथ रिसोर्स।</param>
    /// <param name="vogkResource">वेक्टर ओरिजिनेशन डेटा रिसोर्स।</param>
    /// <param name="socoResource">सॉलिड कलर रिसोर्स।</param>
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
    /// इनपुट लेयर रिसोर्सेज़ में <see cref="VectorPathDataResource"/> रिसोर्स खोजता है।
    /// </summary>
    /// <param name="psdLayer">psd लेयर।</param>
    /// <param name="createIfNotExist">यदि रिसोर्स मौजूद नहीं है, तो <see cref="true"/> के लिए नया रिसोर्स बनाता है, अन्यथा <see cref="null"/> लौटाता है।</param>
    /// <returns><see cref="VectorPathDataResource"/> रिसोर्स।</returns>
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
    /// इनपुट लेयर रिसोर्सेज़ में <see cref="VogkResource"/> रिसोर्स खोजता है।
    /// </summary>
    /// <param name="psdLayer">psd लेयर।</param>
    /// <param name="createIfNotExist">यदि रिसोर्स मौजूद नहीं है, तो <see cref="true"/> के लिए नया रिसोर्स बनाता है, अन्यथा <see cref="null"/> लौटाता है।</param>
    /// <returns><see cref="VogkResource"/> रिसोर्स।</returns>
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
    /// इनपुट लेयर रिसोर्सेज़ में <see cref="SoCoResource"/> रिसोर्स खोजता है।
    /// </summary>
    /// <param name="psdLayer">psd लेयर।</param>
    /// <param name="createIfNotExist">यदि रिसोर्स मौजूद नहीं है, तो <see cref="true"/> के लिए नया रिसोर्स बनाता है, अन्यथा <see cref="null"/> लौटाता है।</param>
    /// <returns><see cref="SoCoResource"/> रिसोर्स।</returns>
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
    /// <see cref="VectorDataProvider"/> क्लास के साथ काम करने के लिए लेयर को वैलिडेट करता है।
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
/// Bezier curve knot, इसमें एक एंकर पॉइंट और दो कंट्रोल पॉइंट्स होते हैं।
/// </summary>
public class BezierKnot
{
    /// <summary>
    /// इमेज से पाथ पॉइंट का अनुपात।
    /// </summary>
    private const int ImgToPsdRatio = 256 * 65535;

    /// <summary>
    /// नया इंस्टेंस इनिशियलाइज़ करता है <see cref="BezierKnot" /> क्लास का।
    /// </summary>
    /// <param name="anchorPoint">एंकर पॉइंट।</param>
    /// <param name="controlPoint1">पहला कंट्रोल पॉइंट।</param>
    /// <param name="controlPoint2">दूसरा कंट्रोल पॉइंट।</param>
    /// <param name="isLinked">यह मान दर्शाता है कि यह नॉट लिंक्ड है या नहीं।</param>
    public BezierKnot(PointF anchorPoint, PointF controlPoint1, PointF controlPoint2, bool isLinked)
    {
        this.AnchorPoint = anchorPoint;
        this.ControlPoint1 = controlPoint1;
        this.ControlPoint2 = controlPoint2;
        this.IsLinked = isLinked;
    }

    /// <summary>
    /// नया इंस्टेंस इनिशियलाइज़ करता है <see cref="BezierKnot" /> क्लास का, जो <see cref="BezierKnotRecord"/> पर आधारित है।
    /// </summary>
    /// <param name="bezierKnotRecord"><see cref="BezierKnotRecord"/>।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
    public BezierKnot(BezierKnotRecord bezierKnotRecord, Size imageSize)
    {
        this.IsLinked = bezierKnotRecord.IsLinked;
        this.ControlPoint1 = ResourcePointToPointF(bezierKnotRecord.Points[0], imageSize);
        this.AnchorPoint = ResourcePointToPointF(bezierKnotRecord.Points[1], imageSize);
        this.ControlPoint2 = ResourcePointToPointF(bezierKnotRecord.Points[2], imageSize);
    }

    /// <summary>
    /// नया इंस्टेंस इनिशियलाइज़ करता है <see cref="BezierKnot" /> क्लास का।
    /// </summary>
    /// <param name="anchorPoint">एंकर और कंट्रोल पॉइंट्स होने वाला पॉइंट।</param>
    /// <param name="isLinked">यह मान दर्शाता है कि यह नॉट लिंक्ड है या नहीं।</param>
    public BezierKnot(PointF anchorPoint, bool isLinked)
    : this(anchorPoint, anchorPoint, anchorPoint, isLinked)
    {
    }

    /// <summary>
    /// यह इंस्टेंस लिंक्ड है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है।
    /// </summary>
    public bool IsLinked { get; set; }

    /// <summary>
    /// पहला कंट्रोल पॉइंट प्राप्त करता है या सेट करता है।
    /// </summary>
    public PointF ControlPoint1 { get; set; }

    /// <summary>
    /// एंकर पॉइंट प्राप्त करता है या सेट करता है।
    /// </summary>
    public PointF AnchorPoint { get; set; }

    /// <summary>
    /// दूसरा कंट्रोल पॉइंट प्राप्त करता है या सेट करता है।
    /// </summary>
    public PointF ControlPoint2 { get; set; }

    /// <summary>
    /// इस इंस्टेंस के आधार पर <see cref="BezierKnotRecord"/> का इंस्टेंस बनाता है।
    /// </summary>
    /// <param name="isClosed">यह दर्शाता है कि यह नॉट बंद आकार में है या नहीं।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
    /// <returns>इस इंस्टेंस के आधार पर <see cref="BezierKnotRecord"/> का इंस्टेंस।</returns>
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
    /// इनपुट मानों द्वारा इस नॉट के पॉइंट्स को शिफ्ट करता है।
    /// </summary>
    /// <param name="xOffset">x ऑफसेट।</param>
    /// <param name="yOffset">y ऑफसेट।</param>
    public void Shift(float xOffset, float yOffset)
    {
        this.ControlPoint1 = new PointF(this.ControlPoint1.X + xOffset, this.ControlPoint1.Y + yOffset);
        this.AnchorPoint = new PointF(this.AnchorPoint.X + xOffset, this.AnchorPoint.Y + yOffset);
        this.ControlPoint2 = new PointF(this.ControlPoint2.X + xOffset, this.ControlPoint2.Y + yOffset);
    }

    /// <summary>
    /// रिसोर्स से सामान्य में पॉइंट मानों को कनवर्ट करता है।
    /// </summary>
    /// <param name="point">रिसोर्स से मानों वाला पॉइंट।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
    /// <returns>सामान्य में कनवर्ट किया गया पॉइंट।</returns>
    private static PointF ResourcePointToPointF(Point point, Size imageSize)
    {
        return new PointF(point.Y / (ImgToPsdRatio / imageSize.Width), point.X / (ImgToPsdRatio / imageSize.Height));
    }

    /// <summary>
    /// सामान्य बिंदु मानों को संसाधन बिंदु में परिवर्तित करता है।
    /// </summary>
    /// <param name="point">बिंदु।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
    /// <returns>संसाधन के लिए मानों के साथ बिंदु।</returns>
    private static Point PointFToResourcePoint(PointF point, Size imageSize)
    {
        return new Point((int)Math.Round(point.Y * (ImgToPsdRatio / imageSize.Height)), (int)Math.Round(point.X * (ImgToPsdRatio / imageSize.Width)));
    }
}

/// <summary>
/// Bezier वक्र के नॉट्स से प्राप्त आकृति।
/// </summary>
public class PathShape
{
    /// <summary>
    /// <see cref="PathShape" /> क्लास का नया उदाहरण प्रारंभ करता है।
    /// </summary>
    public PathShape()
    {
        this.Points = new List<BezierKnot>();
        this.PathOperations = PathOperations.CombineShapes;
    }

    /// <summary>
    /// <see cref="PathShape" /> क्लास का नया उदाहरण <see cref="VectorPathRecord"/> के आधार पर प्रारंभ करता है।
    /// </summary>
    /// <param name="lengthRecord">लंबाई रिकॉर्ड।</param>
    /// <param name="bezierKnotRecords">Bezier नॉट रिकॉर्ड।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
    public PathShape(LengthRecord lengthRecord, List<BezierKnotRecord> bezierKnotRecords, Size imageSize)
    : this()
    {
        this.IsClosed = lengthRecord.IsClosed;
        this.PathOperations = lengthRecord.PathOperations;
        this.ShapeIndex = lengthRecord.ShapeIndex;
        this.InitFromResources(bezierKnotRecords, imageSize);
    }

    /// <summary>
    /// इस उदाहरण के बंद होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है।
    /// </summary>
    /// <value>
    ///   <c>true</c> यदि यह उदाहरण बंद है; अन्यथा, <c>false</c>.
    /// </value>
    public bool IsClosed { get; set; }

    /// <summary>
    /// पथ संचालन (बूलियन संचालन) प्राप्त करता है या सेट करता है।
    /// </summary>
    public PathOperations PathOperations { get; set; }

    /// <summary>
    /// लेयर में वर्तमान पथ आकृति का सूचकांक प्राप्त करता है या सेट करता है।
    /// </summary>
    public ushort ShapeIndex { get; set; }

    /// <summary>
    /// Bezier वक्र के बिंदु प्राप्त करता है।
    /// </summary>
    public List<BezierKnot> Points { get; private set; }

    /// <summary>
    /// इस उदाहरण के आधार पर <see cref="VectorPathRecord"/> रिकॉर्ड बनाता है।
    /// </summary>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
    /// <returns>इस उदाहरण के प्रत्येक बिंदु के लिए एक <see cref="LengthRecord"/> और <see cref="BezierKnotRecord"/> लौटाता है।</returns>
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
    /// इनपुट रिकॉर्ड के आधार पर मान प्रारंभ करता है।
    /// </summary>
    /// <param name="bezierKnotRecords">Bezier नॉट रिकॉर्ड।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
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
/// वह क्लास जो वेक्टर पाथ्स को सम्मिलित करता है।
/// </summary>
public class VectorPath
{
    /// <summary>
    /// <see cref="VectorPath" /> क्लास का नया उदाहरण <see cref="VectorPathDataResource"/> के आधार पर प्रारंभ करता है।
    /// </summary>
    /// <param name="vectorPathDataResource">वेक्टर पाथ डेटा संसाधन।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
    public VectorPath(VectorPathDataResource vectorPathDataResource, Size imageSize)
    {
        this.InitFromResource(vectorPathDataResource, imageSize);
    }

    /// <summary>
    /// यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि भराव सभी पिक्सेल से शुरू होता है या नहीं।
    /// </summary>
    /// <value>
    /// भराव सभी पिक्सेल से शुरू होता है।
    /// </value>
    public bool IsFillStartsWithAllPixels { get; set; }

    /// <summary>
    /// वेक्टर आकृतियों को प्राप्त करता है।
    /// </summary>
    public List<PathShape> Shapes { get; private set; }

    /// <summary>
    /// वेक्टर पाथ भराव रंग प्राप्त करता है या सेट करता है।
    /// </summary>
    public Color FillColor { get; set; }

    /// <summary>
    /// संस्करण प्राप्त करता है या सेट करता है।
    /// </summary>
    /// <value>
    /// संस्करण।
    /// </value>
    public int Version { get; set; }

    /// <summary>
    /// इस उदाहरण के निष्क्रिय होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है।
    /// </summary>
    /// <value>
    ///   <c>true</c> यदि यह उदाहरण निष्क्रिय है; अन्यथा, <c>false</c>.
    /// </value>
    public bool IsDisabled { get; set; }

    /// <summary>
    /// इस उदाहरण के न जुड़े होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है।
    /// </summary>
    /// <value>
    ///   <c>true</c> यदि यह उदाहरण नहीं जुड़ा है; अन्यथा, <c>false</c>.
    /// </value>
    public bool IsNotLinked { get; set; }

    /// <summary>
    /// इस उदाहरण के उलटा होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है।
    /// </summary>
    /// <value>
    ///   <c>true</c> यदि यह उदाहरण उलटा है; अन्यथा, <c>false</c>.
    /// </value>
    public bool IsInverted { get; set; }

    /// <summary>
    /// इनपुट <see cref=\"VectorPathDataResource\"/> संसाधन के आधार पर मानों को प्रारंभ करता है।
    /// </summary>
    /// <param name=\"resource\">वेक्टर पाथ डेटा संसाधन।</param>
    /// <param name="imageSize">पॉइंट कॉर्डिनेट्स को सही रूप में कनवर्ट करने के लिए इमेज साइज।</param>
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

### देखें भी

* class [VmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


