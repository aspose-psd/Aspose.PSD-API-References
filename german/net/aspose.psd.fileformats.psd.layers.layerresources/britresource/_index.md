---
title: "Klasse BritResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource Klasse. Klasse BritResource. Ressource der Helligkeit/Kontrast-Anpassungsebene"
type: docs
weight: 2600
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

Klasse BritResource. Ressource der Helligkeit/Kontrast‑Anpassungsebene.

```csharp
public class BritResource : AdjustmentLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BritResource](britresource/#constructor)() | Initialisiert eine neue Instanz der `BritResource`-Klasse. |
| [BritResource](britresource/#constructor_1)(byte[]) | Initialisiert eine neue Instanz der `BritResource`-Klasse. Die PSD-Format-Spezifikation enthält folgende Beschreibung: 2 Helligkeit 2 Kontrast 2 Mittelwert für Helligkeit und Kontrast 1 Nur Lab-Farbe. Es wird nicht in modernen PSDs (CS5 und höher) verwendet, wo CgEd verwendet wird. CgEd speichert Informations‑Eigenschaften. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Initialisiert eine neue Instanz der `BritResource`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Liest oder schreibt die Helligkeit. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Liest oder schreibt den Kontrast. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Liest oder schreibt den Mittelwert für Helligkeit und Kontrast. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


