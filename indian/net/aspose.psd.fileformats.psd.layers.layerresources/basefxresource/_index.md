---
title: "क्लास BaseFxResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseFxResource क्लास। बेस इफ़ेक्ट्स रिसोर्स"
type: docs
weight: 2550
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/basefxresource/
---
{{< psd/tize >}}
## BaseFxResource class

बेस इफ़ेक्ट्स रिसोर्स

```csharp
public abstract class BaseFxResource : LayerResource
```

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

## उदाहरण

निम्नलिखित कोड मल्टी-इफ़ेक्ट्स संसाधन के समर्थन को दर्शाता है।

```csharp
[C#]

// PSD छवि में 2 ड्रॉप शैडो इफ़ेक्ट्स हैं।
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // यह PSD छवि को 2 ड्रॉप शैडो इफ़ेक्ट्स के साथ रेंडर करता है।
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // यह तीसरा ड्रॉप शैडो इफ़ेक्ट जोड़ता है।
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // यह PSD छवि को 3 ड्रॉप शैडो प्रभावों के साथ रेंडर करता है
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // यदि लेयर में एक ही प्रकार के कई प्रभाव होते हैं तो imfx संसाधन का उपयोग किया जाता है।
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // यह सभी प्रभावों को साफ़ करता है
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // यह PSD छवि को 1 ड्रॉप शैडो प्रभाव के साथ रेंडर करता है (अन्य हटाए गए थे)
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // यदि लेयर में एक ही प्रकार के कई प्रभाव नहीं होते हैं तो lfx2 संसाधन का उपयोग किया जाता है।
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### देखें भी

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


