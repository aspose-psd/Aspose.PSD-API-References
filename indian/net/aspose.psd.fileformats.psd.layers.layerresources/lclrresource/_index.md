---
title: Class LclrResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource कक्ष. वर्ग LclrResource. इस संसधन में परतं क सूच में परत के रंग के बरे में जनकर PS है यह केवल है
type: docs
weight: 2620
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

वर्ग LclrResource. इस संसाधन में परतों की सूची में परत के रंग के बारे में जानकारी PS है। यह केवल है

```csharp
public class LclrResource : LayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`LclrResource` वर्ग. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | का एक नया उदाहरण प्रारंभ करता है`LclrResource` वर्ग. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | का एक नया उदाहरण प्रारंभ करता है`LclrResource` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | परत का रंग प्राप्त या सेट करता है। |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | पीएसडी संस्करण प्राप्त करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | हस्ताक्षर हो जाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | टाइप टूल इंफो की. |

### उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD (शीट रंग सेटिंग) में शीट रंग हाइलाइट को कैसे बदल सकते हैं

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// फाइल में लेयर्स के हाईलाइटिंग के रंग इसी क्रम में होते हैं
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

// लेयर शीट कलर का उपयोग परतों को नेत्रहीन रूप से हाइलाइट करने के लिए किया जाता है। 
// उदाहरण के लिए आप PSD में कुछ परतों को अपडेट कर सकते हैं और फिर उस परत को रंग से हाइलाइट कर सकते हैं जिसे आप ध्यान आकर्षित करना चाहते हैं।
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // रंग उलटा होना चाहिए
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
            // एलसीआरएल संसाधन हमेशा पीएसडी फ़ाइल संसाधन सूची में प्रस्तुत करता है।
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // स्टाइल शीट रंगों का उल्टा। परत रंग हाइलाइट की स्थापना।
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### यह सभी देखें

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


