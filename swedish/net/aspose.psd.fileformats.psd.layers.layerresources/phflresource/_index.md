---
title: Class PhflResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource klass. Klass PhflResource. Resurs för exponeringsjustering Layer 2 Version   3  eller   2  12 4 byte vardera för XYZfärgEndast i version 3 10 2 byte färgrymd följt av 4  2 byte färgkomponent endast 2 4 Density 1 Bevara ljusstyrkan
type: docs
weight: 2890
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Klass PhflResource. Resurs för exponeringsjustering Layer 2 Version ( = 3 ) eller ( = 2 ) 12 4 byte vardera för XYZ-färg(Endast i version 3) 10 2 byte färgrymd följt av 4 * 2 byte färgkomponent (endast 2) 4 Density 1 Bevara ljusstyrkan

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Hämtar eller ställer in densiteten. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Hämtar eller ställer in ett värde som anger om [bevara ljusstyrkan]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Får signaturen. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Hämtar versionen. Standard är 2 eller 3 |

## Metoder

| namn | Beskrivning |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Får färgen på RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Ställer in RGB-färgen. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Typverktygets infonyckel. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


