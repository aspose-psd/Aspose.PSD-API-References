---
title: Class MixrResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource klas. Klasse MixrResource. Ressource der KanalmixerAnpassungsebene
type: docs
weight: 2820
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Klasse MixrResource. Ressource der Kanalmixer-Anpassungsebene

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Initialisiert eine neue Instanz von`MixrResource` class. PSD-Formatspezifikation enthält folgende Beschreibung: 2 Version ( = 1) 2 Monochrom 20 RGB- oder CMYK-Farbe plus Konstante für die Mischereinstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Initialisiert eine neue Instanz von`MixrResource` class. PSD-Formatspezifikation enthält folgende Beschreibung: 2 Version ( = 1) 2 Monochrom 20 RGB- oder CMYK-Farbe plus Konstante für die Mischereinstellungen. 4 * 2 Bytes Farbe mit 2 Bytes Konstante. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist`MixrResource` ist einfarbig. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ruft die Signatur ab. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Ruft die Version ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Ruft die Rohdaten der Kanalinformationen ab |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Legt die Kanalinformationen fest. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


