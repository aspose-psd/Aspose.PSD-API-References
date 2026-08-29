---
title: "Klasse BlwhResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BlwhResource Klasse. BlwhResource‑Klasse ist eine Ressource des Schwarz‑Weiß‑Anpassungslayers."
type: docs
weight: 2580
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---
{{< psd/tize >}}
## BlwhResource class

Die Klasse BlwhResource ist eine Ressource der Schwarz‑und‑Weiß‑Anpassungsebene.

```csharp
public class BlwhResource : AdjustmentLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BlwhResource](blwhresource/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlackAndWhitePresetFileName](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blackandwhitepresetfilename/) { get; set; } | Liest oder setzt den black and white Voreinstellungsdateinamen. |
| [Blues](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/blues/) { get; set; } | Liest oder setzt den blues Wert. |
| [BwPresetKind](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/bwpresetkind/) { get; set; } | Liest oder setzt den black and white Voreinstellungsart Wert. |
| [Cyans](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/cyans/) { get; set; } | Liest oder setzt den cyans Wert. |
| [Greens](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/greens/) { get; set; } | Liest oder setzt den greens Wert. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [Magentas](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/magentas/) { get; set; } | Liest oder setzt den magentas Wert. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| [Reds](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/reds/) { get; set; } | Liest oder setzt den reds Wert. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |
| [TintColor](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/tintcolor/) { get; set; } | Liest oder setzt den ARGB‑Wert der Tönungsfarbe. |
| [UseTint](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/usetint/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [tint color] verwendet wird. |
| [Yellows](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/yellows/) { get; set; } | Liest oder setzt den yellows Wert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/blwhresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

## Beispiele

Das folgende Beispiel zeigt, wie Sie ein BlwhResource bearbeiten.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

const string ActualPropertyValueIsWrongMessage = "Expected property value is not equal to actual value";

string destinationFileName = "Output" + sourceFileName;
bool isRequiredResourceFound = false;
using (PsdImage im = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == tintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == bwPresetKind, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == bwPresetFileName, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue) < 1e-6, ActualPropertyValueIsWrongMessage);

                // Testen von Bearbeitung und Speicherung
                blwhResource.Reds = reds - 15;
                blwhResource.Yellows = yellows - 15;
                blwhResource.Greens = greens + 15;
                blwhResource.Cyans = cyans + 15;
                blwhResource.Blues = blues - 15;
                blwhResource.Magentas = magentas - 15;
                blwhResource.UseTint = !useTint;
                blwhResource.BwPresetKind = 4;
                blwhResource.BlackAndWhitePresetFileName = "bwPresetFileName";
                blwhLayer.TintColorRed = tintColorRed - 60;
                blwhLayer.TintColorGreen = tintColorGreen - 60;
                blwhLayer.TintColorBlue = tintColorBlue - 60;

                im.Save(destinationFileName);
                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");

isRequiredResourceFound = false;

using (PsdImage im = (PsdImage)Image.Load(destinationFileName))
{
    foreach (var layer in im.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            if (layerResource is BlwhResource)
            {
                var blwhResource = (BlwhResource)layerResource;
                var blwhLayer = (BlackWhiteAdjustmentLayer)layer;
                isRequiredResourceFound = true;

                AssertIsTrue(blwhResource.Reds == reds - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Yellows == yellows - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Greens == greens + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Cyans == cyans + 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Blues == blues - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.Magentas == magentas - 15, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.UseTint == !useTint, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.TintColor == newTintColor, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BwPresetKind == 4, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(blwhResource.BlackAndWhitePresetFileName == "bwPresetFileName", ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorRed - tintColorRed + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorGreen - tintColorGreen + 60) < 1e-6, ActualPropertyValueIsWrongMessage);
                AssertIsTrue(Math.Abs(blwhLayer.TintColorBlue - tintColorBlue + 60) < 1e-6, ActualPropertyValueIsWrongMessage);

                break;
            }
        }
    }
}

AssertIsTrue(isRequiredResourceFound, "The specified BlwhResource not found");
```

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


