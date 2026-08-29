---
title: "Klasse PhflResourceVersion2"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 Klasse. Klasse PhflResource. Ressource des Belichtungsanpassungs‑Layers 2 Version 3 oder 2, jeweils 12 4 Bytes für XYZ‑Farbe. Nur in Version 3: 10 2‑Bytes Farbraum gefolgt von 4 2‑Bytes Farbbestandteil. Nur in Version 2: 4 Dichte 1 Luminosität erhalten."
type: docs
weight: 3250
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

Klasse PhflResource. Ressource der Belichtungs-Anpassungsebene 2 Version (= 3) oder (= 2) 12 4 Byte jeweils für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 × 2 Byte Farbbestandteil (nur in Version 2) 4 Dichte 1 Luminanz erhalten.

```csharp
public class PhflResourceVersion2 : PhflResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | Initialisiert eine neue Instanz der `PhflResourceVersion2`‑Klasse. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | Initialisiert eine neue Instanz der `PhflResourceVersion2`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | Liest den Farbraum. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | Liefert oder setzt die A‑Komponente der Farbe |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | Liefert oder setzt die B‑Komponente |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | Liefert oder setzt die L‑Komponente der Farbe |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Liest oder setzt die Dichte. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [Luminanz erhalten] wird. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | Liest die Version. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | Liefert die Farbe. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | Setzt die RGB-Farbe. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


