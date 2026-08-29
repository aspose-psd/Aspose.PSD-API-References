---
title: "Aufzählung SheetColorHighlightEnum"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum Aufzählung. Mögliche Farben der Sheet‑Farbeinstellung. Ihre UI‑Dekorationsfarbe der Ebene in der Ebenenliste in PS."
type: docs
weight: 3320
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

Mögliche Farben der Sheet-Farbeinstellung. Es ist die UI-dekorative Farbe einer Ebene in der Ebenenliste in PS.

```csharp
public enum SheetColorHighlightEnum : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NoColor | `0` | Farbe ist nicht angegeben. |
| Red | `1` | Die rote Farbe. |
| Orange | `2` | Die orange Farbe. |
| Yellow | `3` | Die gelbe Farbe. |
| Green | `4` | Die grüne Farbe. |
| Blue | `5` | Die blaue Farbe. |
| Violet | `6` | Die violette Farbe. |
| Gray | `7` | Die graue Farbe. |

## Beispiele

Das folgende Beispiel zeigt, wie Sie die Blattfarb-Hervorhebung in Aspose.PSD ändern können (Einstellung der Blattfarbe).

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// In der Datei sind die Farben der Ebenen-Hervorhebung in dieser Reihenfolge.
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

// Layer-Blattfarbe wird verwendet, um Ebenen visuell hervorzuheben.
// Zum Beispiel können Sie einige Ebenen in PSD aktualisieren und dann die Ebene, die Sie hervorheben möchten, farblich markieren.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Farben sollten umgekehrt werden.
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
            // Die lcrl-Ressource ist stets in der Ressourcenliste der PSD-Datei vorhanden.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Umkehrung der Stylesheet-Farben. Einrichtung der Ebenenfarb-Hervorhebung.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


