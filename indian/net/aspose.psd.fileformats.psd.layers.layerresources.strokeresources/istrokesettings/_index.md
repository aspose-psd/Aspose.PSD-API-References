---
title: "इंटरफ़ेस IStrokeSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.IStrokeSettings interface. शेप्स की स्ट्रोक सेटिंग्स"
type: docs
weight: 3390
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/
---
{{< psd/tize >}}
## IStrokeSettings interface

शेप्स के स्ट्रोक सेटिंग्स।

```csharp
public interface IStrokeSettings
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/enabled/) { get; set; } | स्ट्रोक सक्षम है। |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/fill/) { get; set; } | स्ट्रोक की फ़िल सेटिंग्स प्राप्त करता या सेट करता है। |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linealignment/) { get; set; } | स्ट्रोक शैली की लाइन संरेखण प्राप्त करता या सेट करता है। |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linecap/) { get; set; } | स्ट्रोक लाइन कैप प्रकार। |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linedashset/) { get; set; } | लाइन डैश की एरे प्राप्त करता या सेट करता है। |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linejoin/) { get; set; } | स्ट्रोक लाइन जॉइन प्रकार। |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/size/) { get; set; } | स्ट्रोक लाइन चौड़ाई। |

## उदाहरण

निम्नलिखित कोड ShapeLayer के लिए vsms या vmsk संसाधनों से पाथ ऑब्जेक्ट्स को दर्शाता है।

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(
    srcFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // एक शेप हटाएँ
    shapes.RemoveAt(1);

    // बदलाव किए डेटा को संसाधन में सहेजें
    List<VectorPathRecord> path = new List<VectorPathRecord>();
    path.Add(new PathFillRuleRecord(null));
    path.Add(new InitialFillRuleRecord(isFillStartsWithAllPixels));

    for (ushort i = 0; i < shapes.Count; i++)
    {
        PathShape shape = (PathShape)shapes[i];
        shape.ShapeIndex = i;
        path.AddRange(shape.ToVectorPathRecords());
    }

    vectorPathDataResource.Paths = path.ToArray();

    image.Save(outFile);
}

// सहेजी गई फ़ाइल में बदलें मानों की जाँच करें
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // सहेजी गई फ़ाइल में 1 शेप होना चाहिए
    AssertAreEqual(1, shapes.Count);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

List<IPathShape> GetShapesFromResource(
    VectorPathDataResource vectorPathDataResource,
    out bool isFillStartsWithAllPixels)
{
    List<IPathShape> shapes = new List<IPathShape>();
    LengthRecord lengthRecord = null;
    isFillStartsWithAllPixels = false;
    List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

    foreach (var pathRecord in vectorPathDataResource.Paths)
    {
        if (pathRecord is LengthRecord)
        {
            if (bezierKnotRecords.Count > 0)
            {
                shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
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
            InitialFillRuleRecord initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            isFillStartsWithAllPixels = initialFillRuleRecord.IsFillStartsWithAllPixels;
        }
    }

    if (bezierKnotRecords.Count > 0)
    {
        shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
        lengthRecord = null;
        bezierKnotRecords.Clear();
    }

    return shapes;
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


