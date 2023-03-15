---
title: Class LinkResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource klass. Definierar klassen LinkResource som innehåller information om länkade eller inbäddade filer i PSDformatbilden. Länkresursen kan innehålla fleraLinkDataSource instanser som kan nås av indexerare i vilken som helst härledd klass.
type: docs
weight: 2710
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

Definierar klassen LinkResource som innehåller information om länkade eller inbäddade filer i PSD-formatbilden. Länkresursen kan innehålla flera[`LinkDataSource`](../linkdatasource/) instanser som kan nås av indexerare i vilken som helst härledd klass.

```csharp
public abstract class LinkResource : LayerResource
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Hämtar antalet länkdatakällor som kan nås av indexeraren. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Får ett värde som indikerar om denna länkresursinstans är tom. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Får[`LinkDataSource`](../linkdatasource/) vid det angivna indexet som är länkdatakällans unika identifierare.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Hämtar PSD:s globala länkresurslängd i byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Hämtar PSD-formatversionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Får PSD:s globala länkresurssignatur. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Sparar resursblockdata. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

### Se även

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


