---
title: "Klasse PhflResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource class. Klasse PhflResource. Ressource des Exposure Adjustment Layer 2 Version   3  oder   2  12 4 Bytes jeweils für XYZ‑FarbeNur in Version 3 10 2 Bytes Farbraum gefolgt von 4  2 Bytes FarbbestandteilNur in Version 2 4 Dichte 1 Leuchtkraft beibehalten."
type: docs
weight: 3240
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

Klasse PhflResource. Ressource der Belichtungs-Anpassungsebene 2 Version (= 3) oder (= 2) 12 4 Byte jeweils für XYZ-Farbe (nur in Version 3) 10 2 Byte Farbraum gefolgt von 4 × 2 Byte Farbbestandteil (nur in Version 2) 4 Dichte 1 Luminanz erhalten.

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Liest oder setzt die Dichte. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [Luminanz erhalten] wird. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Liest die Version. Standard ist 2 oder 3. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Gibt die Farbe des RGB zurück. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Setzt die RGB-Farbe. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


