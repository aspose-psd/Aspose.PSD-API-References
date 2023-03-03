---
title: Enum SheetColorHighlightEnum
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum एनुम. शट रंग सेटंग के संभवत रंग यह PS में परतं क सूच में परत क यूआई सजवट रंग है
type: docs
weight: 2970
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

शीट रंग सेटिंग के संभावित रंग। यह PS में परतों की सूची में परत का यूआई सजावटी रंग है

```csharp
public enum SheetColorHighlightEnum : short
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| NoColor | `0` | रंग निर्दिष्ट नहीं है। |
| Red | `1` | लाल रंग। |
| Orange | `2` | नारंगी रंग। |
| Yellow | `3` | पीला रंग। |
| Green | `4` | हरा रंग। |
| Blue | `5` | नीला रंग। |
| Violet | `6` | बैंगनी रंग। |
| Gray | `7` | ग्रे रंग। |

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

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


