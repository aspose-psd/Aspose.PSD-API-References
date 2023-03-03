---
title: Class LevlResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource klas. Klasse LevelResource. Ressource der Belichtungsanpassungsebene
type: docs
weight: 2640
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

Klasse LevelResource. Ressource der Belichtungsanpassungsebene

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initialisiert eine neue Instanz von`LevlResource` Klasse. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initialisiert eine neue Instanz von`LevlResource` class. Unterstützt in den Farbmodi GrayScale, Duotone, RGB, CMYK, Lab 2 Bytes - Version (=2) 29 * 10 Bytes - Sätze von Ebenendatensätzen mit 5 kurzen Ganzzahlen 4 Bytes - Lvls-Header (Beginnt bei Index 292) 2 Bytes - Version (=3) 2 Bytes - Anzahl der Gesamtlevel-Datensätze 10 * (Gesamtanzahl - 29) Nullende der Level-Ressource sollte auch für vier gefaltet werden |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ruft die Signatur ab. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Ruft die Version ab. Standard ist 2 |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Ruft den Kanal ab. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


