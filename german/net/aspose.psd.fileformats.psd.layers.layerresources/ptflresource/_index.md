---
title: "Klasse PtFlResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource Klasse. Klasse PtFlResource. Enthält Daten des Musterfüll‑Layers."
type: docs
weight: 3310
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
{{< psd/tize >}}
## PtFlResource class

Klasse PtFlResource. Enthält Daten der Muster-Füll-Ebene.

```csharp
public class PtFlResource : FillLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PtFlResource](ptflresource/#constructor)() | Initialisiert eine neue Instanz der `PtFlResource`‑Klasse. |
| [PtFlResource](ptflresource/#constructor_1)(string, string) | Initialisiert eine neue Instanz der `PtFlResource`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/) { get; set; } | Liest oder setzt den Winkel. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob diese Instanz mit dem Layer verknüpft ist. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | Liest oder setzt den Versatz. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | Liest oder setzt die Musterkennung. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | Liest oder setzt den Namen des Musters. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | Liest oder setzt die Skala. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

## Beispiele

Das folgende Beispiel demonstriert die Unterstützung des Ladens und Bearbeitens einer PtFlResource‑Ressource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // Lesen
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // Bearbeiten
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Wir haben keine Musterdaten in PattResource, also können wir sie hinzufügen.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


