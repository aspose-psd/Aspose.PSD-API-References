---
title: Class VectorPathDataResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource कक्ष. क्लस वेक्टरपथडेट रसर्स. इस संसधन में वेक्टर लेयर मस्क के बरे में जनकर है
type: docs
weight: 3340
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
## VectorPathDataResource class

क्लास वेक्टरपाथडेटा रिसोर्स. इस संसाधन में वेक्टर लेयर मास्क के बारे में जानकारी है

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण अक्षम है या नहीं। |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण उल्टा है। |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण लिंक नहीं है। |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | पथ रिकॉर्ड प्राप्त या सेट करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | पीएसडी संस्करण प्राप्त करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | हस्ताक्षर हो जाता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | संस्करण प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

### उदाहरण

निम्न उदाहरण लेयर वेक्टर मास्क प्रोसेसिंग के समर्थन को प्रदर्शित करता है। रास्तों का संपादन कैसे काम करता है और Aspose.PSD अंतिम छवि कैसे बनाता है।

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// अध्ययन
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // वेक्टर पथ बिंदुओं में परिवर्तन करें
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

### यह सभी देखें

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


