---
title: "Klasse CurvResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource Klasse. Klasse CurvResource. Ressource des Kurven‑Anpassungsebenen 1 Byte 0 wenn Kurven verwendet werden 1 wenn Pixel auf der Karte verwendet werden, wenn 0 dann 2 Bytes short. Standard ist 1 4 Bytes int. Nur das letzte Byte wird bitweise verwendet. Das erste Bit steht für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 2 Bytes short Punktzahl 4 Bytes Anzahl der Punkte der Kurve 2 short erste Position zweite Höhe 4 Bytes Wort Crv 2 Bytes short Standard ist 4 für Kurven 4 Bytes int. Standard ist 1 4 Bytes Punktzahl 4 Bytes Punktzahl Punkte der Kurve 2 short erste Position zweite Höhe 04 Bytes Führend zu Falz für vier, wenn 1 dann 2 Bytes short. Standard ist 1 4 Bytes int. Nur das letzte Byte wird verwendet. Ein Kanal ist in einem Bit. Das erste Bit steht für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 256 Anzahl geänderter Kanäle geordnete Werte des Kanals im Bereich 0‑255 4 Bytes Wort Crv 2 Bytes short. Standard ist 3 für Pixel auf der Karte 4 Bytes int Kanalanzahl 2 256 Bytes short 2 für Kanalindex 256 ist geordnete Werte des Kanals im Bereich 0‑255"
type: docs
weight: 2660
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Klasse CurvResource. Ressource der Kurven‑Anpassungsebene 1 Byte – 0, wenn Kurven verwendet werden, 1, wenn Pixel auf der Karte verwendet werden; wenn 0, dann: 2 Bytes – short. Standard ist 1. 4 Bytes – int. Nur das letzte Byte wird bitweise verwendet. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 2 Bytes – short Punktanzahl. 4 Bytes * Anzahl der Punkte – Punkte der Kurve. 2 short: erste Position, zweite Höhe. 4 Bytes – Wort "Crv ". 2 Bytes – short, Standard ist 4 für Kurven. 4 Bytes – int. Standard ist 1. 4 Bytes – Punktanzahl. 4 Bytes * Punktanzahl – Punkte der Kurve. 2 short: erste Position, zweite Höhe. 0‑4 Bytes – führend, um für vier zu falten, wenn 1, dann: 2 Bytes – short. Standard ist 1. 4 Bytes – int. Nur das letzte Byte wird verwendet. Ein Kanal ist in einem Bit. Das erste Bit ist für 1 Kanal, das vierte Bit für 4 Kanäle, zum Beispiel 256 * Anzahl der geänderten Kanäle – geordnete Werte des Kanals im Bereich 0‑255. 4 Bytes – Wort "Crv ". 2 Bytes – short. Standard ist 3 für Pixel auf der Karte. 4 Bytes – int Kanalanzahl (2 + 256) Bytes – short 2 für Kanal‑Index, 256 sind geordnete Werte des Kanals im Bereich 0‑255.

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Initialisiert eine neue Instanz der `CurvResource`‑Klasse. |
| [CurvResource](curvresource/#constructor_1)(int) | Initialisiert eine neue Instanz der `CurvResource`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz diskret gespeicherte Daten enthält. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Ruft den aktiven Manager ab. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Ruft die Kanal‑Daten ab. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Ruft den Kurven‑Manager ab. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


