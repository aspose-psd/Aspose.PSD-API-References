---
title: "Klass LinkResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource-klass. Definierar LinkResource-klassen som innehåller information om länkade eller inbäddade filer i PSD‑formatets bild. Länkresursen kan innehålla flera LinkDataSource‑instanser som kan nås via indexerare i alla avledda klasser."
type: docs
weight: 3010
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Definierar LinkResource-klassen som innehåller information om länkade eller inbäddade filer i PSD‑formatets bild. Länkresursen kan innehålla flera [`LinkDataSource`](../linkdatasource/)‑instanser som kan nås via indexerare i alla avledda klasser.

```csharp
public abstract class LinkResource : LayerResource
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Hämtar antalet länkdatakällor som kan nås via indexer. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Hämtar ett värde som indikerar om denna länkresursinstans är tom. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Hämtar [`LinkDataSource`](../linkdatasource/) på det angivna indexet som är den unika identifieraren för länkdatasourcen. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Hämtar den globala PSD‑länkresursens längd i byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Sparar resursblockets data. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

### Se även

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


