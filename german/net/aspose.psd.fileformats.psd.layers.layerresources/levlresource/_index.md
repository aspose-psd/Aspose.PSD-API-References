---
title: "Klasse LevlResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource Klasse. Klasse LevlResource. Ressource der Belichtungs‑Anpassungsebene"
type: docs
weight: 2950
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Klasse LevlResource. Ressource der Belichtungs-Anpassungsebene.

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initialisiert eine neue Instanz der `LevlResource`-Klasse. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initialisiert eine neue Instanz der `LevlResource`-Klasse. Unterstützt in den Farbmodi GrayScale, Duotone, RGB, CMYK, Lab 2 Byte - Version (=2) 29 * 10 Byte - Sätze von Level‑Datensätzen mit 5 Kurz‑Integern 4 Byte - Lvls‑Header (beginnt bei Index 292) 2 Byte - Version (=3) 2 Byte - Anzahl der gesamten Level‑Datensätze 10 * (Gesamtzahl - 29) Null‑Endung der Lvls‑Ressource sollte ebenfalls für vier gefaltet werden |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Liest die Version. Standard ist 2. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Liest den Kanal. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


