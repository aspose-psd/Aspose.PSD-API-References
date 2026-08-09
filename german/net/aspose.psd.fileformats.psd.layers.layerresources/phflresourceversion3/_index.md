---
title: "Klasse PhflResourceVersion3"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3 Klasse. Klasse PhflResource. Ressource des Exposure Adjustment Layer 2 Version   3 oder   2 12 4 Bytes jeweils für XYZ-FarbeNur in Version 3 10 2 Bytes Farbraum gefolgt von 4  2 Bytes FarbbestandteilNur in Version 2 4 Dichte 1 Preserve Luminosity"
type: docs
weight: 3260
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

Klasse PhflResource. Ressource der Belichtungs-Anpassungsebene 2 Version (= 3) oder (= 2) 12 4 Byte jeweils für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 × 2 Byte Farbbestandteil (nur in Version 2) 4 Dichte 1 Luminanz erhalten.

```csharp
public class PhflResourceVersion3 : PhflResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | Initialisiert eine neue Instanz der `PhflResourceVersion3` Klasse. |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | Initialisiert eine neue Instanz der `PhflResourceVersion3` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | Liest den Farbraum. |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | Liest oder setzt die X-Farbe. |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | Liest oder setzt die Y-Farbe. |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | Liest oder setzt die Z-Farbe. |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Liest oder setzt die Dichte. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [Luminanz erhalten] wird. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | Liest die Version. Standard ist 2 oder 3. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | Liefert die Farbe. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | Setzt die RGB-Farbe. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


