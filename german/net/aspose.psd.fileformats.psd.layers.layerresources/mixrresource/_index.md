---
title: "Klasse MixrResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource class. Klasse MixrResource. Ressource des Channel Mixer Adjustment Layer."
type: docs
weight: 3160
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Klasse MixrResource. Ressource der Kanal-Mischer-Anpassungsebene.

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Initialisiert eine neue Instanz der `MixrResource` Klasse. Die PSD-Formatspezifikation enthält die folgende Beschreibung: 2 Version (= 1) 2 Monochrom 20 RGB‑ oder CMYK‑Farbe plus Konstante für die Mixer‑Einstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Initialisiert eine neue Instanz der `MixrResource` Klasse. Die PSD-Formatspezifikation enthält die folgende Beschreibung: 2 Version (= 1) 2 Monochrom 20 RGB‑ oder CMYK‑Farbe plus Konstante für die Mixer‑Einstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob dieses `MixrResource` monochrom ist. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Ruft die Version ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Liest die Rohdaten der Kanalinformationen |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Setzt die Kanalinformationen. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


