---
title: Class CurvResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource klass. Klass CurvResource. Resurs för kurvjustering Layer 1 byte  0 om kurvor används 1 om använda pixlar på map om 0 då 2 byte  kort. Standard är 1 4 byte  int. Används endast sista byte för bit. Första biten är för 1 kanal den fjärde biten för 4 kanal till exempel 2 byte  korta punkter count 4 bytes  antal punkt  punkter på kurva 2 kort första positionen andra höjd 4 byte  ordet Crv  2 bytes  kort standard är 4 för Curves 4 byte  int. Standard är 1 4 byte  antal poäng 4 bytes  antal poäng  punkter i kurva 2 kort första position andra höjd 04 byte  Ledande att vikas för fyra om 1 sedan 2 bytes  kort. Standard är 1 4 byte  int. Används endast sista byten. En kanal är i en bit. Första biten är för 1 kanal den fjärde biten för 4 kanaler till exempel 256  antal ändrade kanaler  ordnade värden för kanalen i intervallet 0  255 4 byte  ordet Crv  2 byte  kort. Standard är 3 för pixlar på map 4 byte  int Channel count 2  256 byte  kort 2 för kanalindex 256 är ordnade värden för kanal i intervallet 0  255
type: docs
weight: 2400
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Klass CurvResource. Resurs för kurvjustering Layer 1 byte - 0 om kurvor används, 1 om använda pixlar på map om 0 då: 2 byte - kort. Standard är 1 4 byte - int. Används endast sista byte för bit. Första biten är för 1 kanal, den fjärde biten för 4 kanal till exempel 2 byte - korta punkter count 4 bytes * antal punkt - punkter på kurva 2 kort: första positionen, andra höjd 4 byte - ordet "Crv " 2 bytes - kort standard är 4 för Curves 4 byte - int. Standard är 1 4 byte - antal poäng 4 bytes * antal poäng - punkter i kurva 2 kort: första position, andra höjd 0-4 byte - Ledande att vikas för fyra om 1 sedan: 2 bytes - kort. Standard är 1 4 byte - int. Används endast sista byten. En kanal är i en bit. Första biten är för 1 kanal, den fjärde biten för 4 kanaler till exempel 256 * antal ändrade kanaler - ordnade värden för kanalen i intervallet 0 - 255 4 byte - ordet "Crv " 2 byte - kort. Standard är 3 för pixlar på map 4 byte - int Channel count (2 + 256) byte - kort 2 för kanalindex, 256 är ordnade värden för kanal i intervallet 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Initierar en ny instans av`CurvResource` class. |
| [CurvResource](curvresource/#constructor_1)(int) | Initierar en ny instans av`CurvResource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är data lagrad diskret. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Får signaturen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Hämtar den aktiva hanteraren. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Hämtar kanaldata. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Hämtar kurvhanteraren. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Typverktygets infonyckel. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


