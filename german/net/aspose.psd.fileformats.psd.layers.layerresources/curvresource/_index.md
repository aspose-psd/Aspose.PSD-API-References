---
title: Class CurvResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource klas. Klasse CurvResource. Ressource für Kurvenanpassungsebene 1 Byte  0 wenn Kurven verwendet werden 1 wenn Pixel auf der Karte verwendet werden  wenn 0 dann 2 Bytes  kurz. Standard ist 1 4 Bytes  int. Nur letztes Byte für Bit verwendet. Das erste Bit ist für 1 Kanal das vierte Bit für 4 Kanäle zum Beispiel 2 Bytes  Anzahl der kurzen Punkte 4 Bytes  Anzahl der Punkte  Punkte der Kurve 2 kurz erste Position zweite Höhe 4 Bytes  Wort Crv 2 Bytes  short Standard ist 4 für Curves 4 Bytes  int. Standard ist 1 4 Bytes  Punktzahl 4 Bytes  Punktzahl  Punkte von Kurve 2 kurz erste Position zweite Höhe 04 Bytes  Leading to be fold for four wenn 1 dann 2 Bytes  kurz. Standard ist 1 4 Bytes  int. Nur letztes Byte verwendet. Ein Kanal ist in einem Bit. Das erste Bit ist für 1 Kanal das vierte Bit für 4 Kanäle zum Beispiel 256  Anzahl der geänderten Kanäle  geordnete Werte des Kanals im Bereich 0  255 4 Bytes  Wort Crv  2 Bytes  kurz. Standard ist 3 für Pixel auf map 4 Bytes  int Channel count 2  256 Bytes  kurz 2 für Kanalindex 256 sind geordnete Werte des Kanals im Bereich 0  255
type: docs
weight: 2400
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Klasse CurvResource. Ressource für Kurvenanpassungsebene 1 Byte - 0, wenn Kurven verwendet werden, 1, wenn Pixel auf der Karte verwendet werden , wenn 0, dann: 2 Bytes - kurz. Standard ist 1 4 Bytes - int. Nur letztes Byte für Bit verwendet. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 2 Bytes – Anzahl der kurzen Punkte 4 Bytes * Anzahl der Punkte – Punkte der Kurve 2 kurz: erste Position, zweite Höhe 4 Bytes – Wort „Crv“ 2 Bytes – short Standard ist 4 für Curves 4 Bytes - int. Standard ist 1 4 Bytes - Punktzahl 4 Bytes * Punktzahl - Punkte von Kurve 2 kurz: erste Position, zweite Höhe 0-4 Bytes - Leading to be fold for four wenn 1 dann: 2 Bytes - kurz. Standard ist 1 4 Bytes - int. Nur letztes Byte verwendet. Ein Kanal ist in einem Bit. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 256 * Anzahl der geänderten Kanäle - geordnete Werte des Kanals im Bereich 0 - 255 4 Bytes - Wort "Crv " 2 Bytes - kurz. Standard ist 3 für Pixel auf map 4 Bytes - int Channel count (2 + 256) Bytes - kurz 2 für Kanalindex, 256 sind geordnete Werte des Kanals im Bereich 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Initialisiert eine neue Instanz von`CurvResource` Klasse. |
| [CurvResource](curvresource/#constructor_1)(int) | Initialisiert eine neue Instanz von`CurvResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob es sich bei dieser Instanz um diskret gespeicherte Daten handelt. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ruft die Signatur ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Ruft den aktiven Manager ab. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Ruft die Kanaldaten ab. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Ruft den Kurvenmanager ab. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


