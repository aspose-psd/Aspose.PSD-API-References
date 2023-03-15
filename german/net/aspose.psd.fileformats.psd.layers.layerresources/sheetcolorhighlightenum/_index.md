---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum opsomming. Mögliche Farben der Blattfarbeinstellung. Dies ist die dekorative Farbe der Benutzeroberfläche der Ebene in der Ebenenliste in PS
type: docs
weight: 2970
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

Mögliche Farben der Blattfarbeinstellung. Dies ist die dekorative Farbe der Benutzeroberfläche der Ebene in der Ebenenliste in PS

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

### Beispiele

Das folgende Beispiel zeigt, wie Sie die Blattfarbhervorhebung in Aspose.PSD (Blattfarbeinstellung) ändern können.

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// In der Datei sind die Farben der Ebenenhervorhebung in dieser Reihenfolge
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

// Layer Sheet Color wird verwendet, um Layer visuell hervorzuheben. 
// Zum Beispiel können Sie einige Ebenen in PSD aktualisieren und dann die Ebene, die Sie hervorheben möchten, farblich hervorheben.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Farben sollten umgekehrt werden
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
            // Die lcrl-Ressource wird immer in der Ressourcenliste der PSD-Datei angezeigt.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Umkehrung der Stylesheet-Farben. Einrichtung der Ebenenfarbhervorhebung.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


