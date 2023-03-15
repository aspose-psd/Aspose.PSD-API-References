---
title: Class VibAResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource klas. VibARessource.
type: docs
weight: 3350
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
## VibAResource class

VibA-Ressource.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [VibAResource](vibaresource/)() | Initialisiert eine neue Instanz von`VibAResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Byte ab. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | Ruft den Sättigungswert ab oder setzt ihn |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ruft die Signatur ab. |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | Ruft den Vibrationswert ab oder legt ihn fest |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

### Beispiele

Das folgende Codebeispiel demonstriert die Unterstützung der VibAResource-Ressource.

```csharp
[C#]

// Beispiel für die Unterstützung des Lesens und Schreibens von Vibrationsressourcen zur Laufzeit.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


