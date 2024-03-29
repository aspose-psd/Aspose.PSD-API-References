---
title: Class BritResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource klas. Klasse BritResource. Ressource der Helligkeits/Kontrastanpassungsebene
type: docs
weight: 2340
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

Klasse BritResource. Ressource der Helligkeits-/Kontrastanpassungsebene

```csharp
public class BritResource : AdjustmentLayerResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BritResource](britresource/#constructor)() | Initialisiert eine neue Instanz von`BritResource` Klasse. |
| [BritResource](britresource/#constructor_1)(byte[]) | Initialisiert eine neue Instanz von`BritResource`class. Die PSD-Formatspezifikation enthält folgende Beschreibung: 2 Helligkeit 2 Kontrast 2 Mittelwert für Helligkeit und Kontrast 1 Nur Lab-Farbe Wird in modernen PSDs (CS5 und höher) nicht verwendet, wo CgEd ist. CgEd speichert Informationen properties |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Initialisiert eine neue Instanz von`BritResource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Ruft die Helligkeit ab oder setzt sie. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Ruft den Kontrast ab oder legt ihn fest. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key/) { get; } | Ruft den Layer-Ressourcenschlüssel ab. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Laborfarbe]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Ruft die Layer-Ressourcenlänge in Bytes ab. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Liest oder setzt den Mittelwert für Helligkeit und Kontrast. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion/) { get; } | Ruft die PSD-Version ab. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ruft die Signatur ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Speichert die Ressource im angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Der Typ-Tool-Info-Schlüssel. |

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


