---
title: Class SoCoResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource कक्ष. वर्ग SoCoResource. इस संसधन में रंग भरने वल परतं के बरे में जनकर है
type: docs
weight: 3010
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

वर्ग SoCoResource. इस संसाधन में रंग भरने वाली परतों के बारे में जानकारी है

```csharp
public class SoCoResource : FillLayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SoCoResource](socoresource/)() | का एक नया उदाहरण प्रारंभ करता है`SoCoResource` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | आरजीबी रंग प्राप्त करता है . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | परत संसाधन के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 कोई प्रतिबंध नहीं दर्शाता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | परत संसाधन हस्ताक्षर प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | टाइप टूल इंफो की. |

### उदाहरण

निम्न उदाहरण प्रदर्शित करता है कि आप SoCoResource (रंग भरण परत के लिए परत संसाधन) को कैसे संपादित करते हैं

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // फिललेयर की खोज
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // लेयर रिसोर्स लिस्ट में SoCoResource का पता लगाना
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource कलर प्रॉपर्टी सेट करना
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### यह सभी देखें

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


