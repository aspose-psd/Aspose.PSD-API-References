---
title: Class LclrResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource klas. Klasse LclrResource. Diese Ressource enthält Informationen über die Farbe der Ebene in der Liste der Ebenen ist PS. Es ist nur
type: docs
weight: 2620
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Klasse LclrResource. Diese Ressource enthält Informationen über die Farbe der Ebene in der Liste der Ebenen ist PS. Es ist nur

```csharp
public class LclrResource : LayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Initialisiert eine neue Instanz von`LclrResource` Klasse. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Initialisiert eine neue Instanz von`LclrResource` Klasse. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Initialisiert eine neue Instanz von`LclrResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Ruft die Farbe der Ebene ab oder legt sie fest. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | Ruft die Signatur ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


