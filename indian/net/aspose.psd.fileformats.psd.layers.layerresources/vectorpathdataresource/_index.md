---
title: "क्लास VectorPathDataResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource क्लास। क्लास VectorPathDataResource। यह संसाधन वेक्टर लेयर मास्क के बारे में जानकारी रखता है।"
type: docs
weight: 3740
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
{{< psd/tize >}}
## VectorPathDataResource class

क्लास VectorPathDataResource। यह संसाधन वेक्टर लेयर मास्क के बारे में जानकारी रखता है।

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | इस इंस्टेंस के निष्क्रिय होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | इस इंस्टेंस के उल्टे होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | इस इंस्टेंस के न जुड़े होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | पाथ रिकॉर्ड्स को प्राप्त करता है या सेट करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | संस्करण को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## उदाहरण

निम्न उदाहरण लेयर वेक्टर मास्क प्रोसेसिंग के समर्थन को दर्शाता है। पाथ्स के संपादन कैसे काम करता है और Aspose.PSD अंतिम छवि कैसे बनाता है।

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// पढ़ना
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // वेक्टर पाथ बिंदुओं में परिवर्तन करें
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // निर्यात
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### देखें भी

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


