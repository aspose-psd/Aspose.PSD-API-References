---
title: "क्लास IfxsResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource क्लास। Ifxs रिसोर्स ग्रुप लेयर इफ़ेक्ट्स रिसोर्स"
type: docs
weight: 2840
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ifxs रिसोर्स (ग्रुप लेयर इफ़ेक्ट्स रिसोर्स)।

```csharp
public sealed class IfxsResource : BaseFxResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [IfxsResource](ifxsresource/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | डिस्क्रिप्टर संस्करण को प्राप्त करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

## उदाहरण

निम्नलिखित कोड IfxsResource के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // उदाहरण में प्रभावों के साथ 2 समूह लेयर हैं
    // एक प्रभाव वाला समूह लेयर
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // कई प्रभावों वाला समूह लेयर
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // इफ़ेक्ट्स की संख्या प्राप्त करें और उनकी मात्रा सत्यापित करें
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // ग्रुप लेयर में एक इफ़ेक्ट संसाधन 'IfxsResource' में है
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // ग्रुप लेयर में दो या अधिक इफ़ेक्ट्स संसाधन 'ImfxResource' में हैं
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // कई इफ़ेक्ट्स वाले ग्रुप लेयर में तीसरा शैडो जोड़ें
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### देखें भी

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


