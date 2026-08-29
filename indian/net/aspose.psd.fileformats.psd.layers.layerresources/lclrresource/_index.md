---
title: "क्लास LclrResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource क्लास। क्लास LclrResource। यह रिसोर्स लेयर की सूची में लेयर के रंग के बारे में जानकारी रखता है PS में। यह केवल"
type: docs
weight: 2930
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
{{< psd/tize >}}
## LclrResource class

क्लास LclrResource. यह रिसोर्स लेयर्स की सूची में लेयर के रंग के बारे में जानकारी रखता है, जो PS में है। यह केवल

```csharp
public class LclrResource : LayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | `LclrResource` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | `LclrResource` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | `LclrResource` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | लेयर के रंग को प्राप्त करता है या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि आप Aspose.PSD में शीट रंग हाइलाइट (शीट रंग सेटिंग) को कैसे बदल सकते हैं।

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// फ़ाइल में लेयरों के हाइलाइटिंग के रंग इस क्रम में हैं।
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// लेयर शीट रंग का उपयोग लेयरों को दृश्य रूप से हाइलाइट करने के लिए किया जाता है।
// उदाहरण के लिए आप PSD में कुछ लेयरों को अपडेट कर सकते हैं और फिर उस लेयर को रंग से हाइलाइट कर सकते हैं जिसे आप ध्यान आकर्षित करना चाहते हैं।
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // रंगों को उलटा होना चाहिए
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // lcrl संसाधन हमेशा PSD फ़ाइल संसाधन सूची में मौजूद रहता है।
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // स्टाइल शीट रंगों का उलटा। लेयर रंग हाइलाइट की सेटिंग।
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### देखें भी

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


