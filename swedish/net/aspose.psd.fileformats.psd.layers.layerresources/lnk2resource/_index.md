---
title: "Klass Lnk2Resource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource-klass. Definierar klassen som innehåller information om inbäddade filer i PSD-formatets bild. Länkretsursen kan innehålla flera LiFdDataSource‑instanser som kan nås via indexeraren"
type: docs
weight: 3030
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

Definierar klassen som innehåller information om inbäddade filer i PSD-formatets bild. Länkretsursen kan innehålla flera [`LiFdDataSource`](../lifddatasource/)‑instanser som kan nås via indexeraren.

```csharp
public class Lnk2Resource : LinkResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | Initierar en ny instans av klassen `Lnk2Resource`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Hämtar antalet länkdatakällor som kan nås via indexer. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Hämtar ett värde som indikerar om denna länkresursinstans är tom. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Hämtar [`LiFdDataSource`](../lifddatasource/) på det angivna indexet. (2 indexers) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Hämtar den globala PSD‑länkresursens längd i byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Sparar resursblockets data. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | Typverktygsinformationsnyckeln. |

### Se även

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


