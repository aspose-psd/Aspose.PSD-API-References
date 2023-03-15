---
title: LclrResource.Color
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LclrResource संपत्त. परत क रंग प्रप्त य सेट करत है
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

परत का रंग प्राप्त या सेट करता है।

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### संपत्ति मूल्य

रंग.

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

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* सभा [Aspose.PSD](../../../)


