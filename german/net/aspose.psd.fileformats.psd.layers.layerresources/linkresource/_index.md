---
title: "Klasse LinkResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource Klasse. Definiert die LinkResource Klasse, die Informationen über verknüpfte oder eingebettete Dateien im PSD‑Format‑Bild enthält. Die Link‑Ressource kann mehrere LinkDataSource‑Instanzen enthalten, auf die über Indexer in jeder abgeleiteten Klasse zugegriffen werden kann."
type: docs
weight: 3010
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Definiert die LinkResource Klasse, die Informationen über verknüpfte oder eingebettete Dateien im PSD‑Format‑Bild enthält. Die Link‑Ressource kann mehrere [`LinkDataSource`](../linkdatasource/) Instanzen enthalten, auf die über Indexer in jeder abgeleiteten Klasse zugegriffen werden kann.

```csharp
public abstract class LinkResource : LayerResource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Liest die Anzahl der Link‑Datenquellen, auf die über den Indexer zugegriffen werden kann. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Liest einen Wert, der angibt, ob diese Link‑Ressourcen‑Instanz leer ist. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Liest das [`LinkDataSource`](../linkdatasource/) am angegebenen Index, das die eindeutige Kennung der Link‑Datenquelle ist.. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Ermittelt die Länge der globalen PSD-Link-Ressource in Bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Speichert die Daten des Ressourcenblocks. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


