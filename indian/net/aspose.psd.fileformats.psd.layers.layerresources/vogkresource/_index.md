---
title: Class VogkResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource कक्ष. वेक्टर उत्पत्त डेट संसधन
type: docs
weight: 3370
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
## VogkResource class

वेक्टर उत्पत्ति डेटा संसाधन।

```csharp
public sealed class VogkResource : LayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [VogkResource](vogkresource/)() | का एक नया उदाहरण प्रारंभ करता है`VogkResource` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/) { get; } | परत संसाधन के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 कोई प्रतिबंध नहीं दर्शाता है। |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | आकार की मूल सेटिंग प्राप्त या सेट करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/signature/) { get; } | परत संसाधन हस्ताक्षर प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | संस्करण प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | टाइप टूल इंफो की. |

### उदाहरण

निम्न उदाहरण VogkResource संसाधन के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // अध्ययन
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // संपादन
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### यह सभी देखें

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


