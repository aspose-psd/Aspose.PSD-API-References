---
title: "Klasse LclrResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource Klasse. Klasse LclrResource. Diese Ressource enthält Informationen über die Farbe der Ebene in der Ebenenliste von PS. Sie ist nur"
type: docs
weight: 2930
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
{{< psd/tize >}}
## LclrResource class

Klasse LclrResource. Diese Ressource enthält Informationen über die Farbe der Ebene in der Ebenenliste von PS. Es ist nur

```csharp
public class LclrResource : LayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Initialisiert eine neue Instanz der `LclrResource` Klasse. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Initialisiert eine neue Instanz der `LclrResource` Klasse. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Initialisiert eine neue Instanz der `LclrResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Liest oder setzt die Farbe der Ebene. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


