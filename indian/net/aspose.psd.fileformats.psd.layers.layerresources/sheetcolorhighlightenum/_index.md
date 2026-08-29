---
title: "एनम SheetColorHighlightEnum"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum एनम। शीट रंग सेटिंग के संभावित रंग। यह PS में लेयर सूची में लेयर का UI सजावटी रंग है।"
type: docs
weight: 3320
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

शीट रंग सेटिंग के संभावित रंग। यह PS में लेयर्स की सूची में लेयर का UI सजावटी रंग है।

```csharp
public enum SheetColorHighlightEnum : short
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| NoColor | `0` | रंग निर्दिष्ट नहीं है। |
| Red | `1` | लाल रंग। |
| Orange | `2` | नारंगी रंग। |
| Yellow | `3` | पीला रंग। |
| Green | `4` | हरा रंग। |
| Blue | `5` | नीला रंग। |
| Violet | `6` | बैंगनी रंग। |
| Gray | `7` | धूसर रंग। |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


