---
title: "Klasse Lnk2Resource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource Klasse. Definiert die Klasse, die Informationen über eingebettete Dateien im PSD-Format-Bild enthält. Die Link-Ressource kann mehrere LiFdDataSource-Instanzen enthalten, auf die über den Indexer zugegriffen werden kann."
type: docs
weight: 3030
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

Definiert die Klasse, die Informationen über eingebettete Dateien im PSD-Format-Bild enthält. Die Link-Ressource kann mehrere [`LiFdDataSource`](../lifddatasource/) Instanzen enthalten, auf die über den Indexer zugegriffen werden kann.

```csharp
public class Lnk2Resource : LinkResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | Initialisiert eine neue Instanz der `Lnk2Resource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Liest die Anzahl der Link‑Datenquellen, auf die über den Indexer zugegriffen werden kann. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Liest einen Wert, der angibt, ob diese Link‑Ressourcen‑Instanz leer ist. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Liest das [`LiFdDataSource`](../lifddatasource/) am angegebenen Index. (2 Indexer) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Ermittelt die Länge der globalen PSD-Link-Ressource in Bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Speichert die Daten des Ressourcenblocks. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


