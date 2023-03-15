---
title: Class BritResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource klass. Klass BritResource. Resurs för ljusstyrka/kontrastjustering Layer
type: docs
weight: 2340
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

Klass BritResource. Resurs för ljusstyrka/kontrastjustering Layer

```csharp
public class BritResource : AdjustmentLayerResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [BritResource](britresource/#constructor)() | Initierar en ny instans av`BritResource` class. |
| [BritResource](britresource/#constructor_1)(byte[]) | Initierar en ny instans av`BritResource`class. PSD-formatspecifikationen innehåller följande beskrivning: 2 Brightness 2 Contrast 2 Medelvärde för ljusstyrka och kontrast 1 Lab color only Den används inte i modern PSD (CS5 och uppåt) där CgEd är. CgEd lagrar info properties |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Initierar en ny instans av`BritResource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Hämtar eller ställer in ljusstyrkan. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Hämtar eller ställer in kontrasten. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Hämtar eller ställer in ett värde som anger om [labbfärg]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Hämtar eller ställer in medelvärdet för ljusstyrka och kontrast. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Får signaturen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Typverktygets infonyckel. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


