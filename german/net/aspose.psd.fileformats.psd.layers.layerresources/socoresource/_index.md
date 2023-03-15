---
title: Class SoCoResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource klas. Klasse SoCoResource. Diese Ressource enthält Informationen zu Farbfüllebenen
type: docs
weight: 3010
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Klasse SoCoResource. Diese Ressource enthält Informationen zu Farbfüllebenen

```csharp
public class SoCoResource : FillLayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SoCoResource](socoresource/)() | Initialisiert eine neue Instanz von`SoCoResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | Ruft die RGB-Farbe ab . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | Ruft die minimale PSD-Version ab, die für die Layer-Ressource erforderlich ist. 0 zeigt keine Einschränkungen an. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | Ruft die Layer-Ressourcensignatur ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie SoCoResource (Ebenenressource für Farbfüllungsebene) bearbeiten.

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Finden von FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Finden von SoCoResource in der Layer-Ressourcenliste
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Festlegen der SoCoResource Color-Eigenschaft
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


