---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum enum. Possible colors of Sheet color setting. Its UI decorative color of layer in layers list in PS
type: docs
weight: 3220
url: /net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

Possible colors of Sheet color setting. It's UI decorative color of layer in layers' list in PS

```csharp
public enum SheetColorHighlightEnum : short
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoColor | `0` | Color is not specified. |
| Red | `1` | The red color. |
| Orange | `2` | The orange color. |
| Yellow | `3` | The yellow color. |
| Green | `4` | The green color. |
| Blue | `5` | The blue color. |
| Violet | `6` | The violet color. |
| Gray | `7` | The gray color. |

## Examples

The following example demonstrates how you can change Sheet Color Highlight In Aspose.PSD (Sheet color setting)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// In the file colors of layers' highlighting are in this order
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

// Layer Sheet Color is used to visually highlight layers. 
// For example you can update some layers in PSD and then highlight by color the layer which you want to attract attention.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Colors should be reversed
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
            // The lcrl resource always presents in psd file resource list.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Reverse of style sheet colors. Set up of Layer color highlight.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


