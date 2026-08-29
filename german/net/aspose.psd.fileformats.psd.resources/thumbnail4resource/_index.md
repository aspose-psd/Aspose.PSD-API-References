---
title: "Klasse Thumbnail4Resource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Resources.Thumbnail4Resource Klasse. Stellt die Thumbnail‑Ressource für PSD 4.0 dar"
type: docs
weight: 4360
url: /de/net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---
{{< psd/tize >}}
## Thumbnail4Resource class

Stellt die Thumbnail-Ressource für psd 4.0 dar.

```csharp
public sealed class Thumbnail4Resource : ThumbnailResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Thumbnail4Resource](thumbnail4resource/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | Liest oder setzt die Bits pro Pixel. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | Ruft die Größe der Ressourcendaten in Bytes ab. |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | Liest oder setzt das Thumbnail-Datenformat. |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | Liest oder setzt die Höhe des Thumbnails in Pixeln. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung der Ressource ab oder legt sie fest. |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | Liest oder setzt die JPEG-Optionen. Geeignet, wenn die Thumbnail-Ressource ausschließlich im JPEG-Dateiformat gespeichert wird. Diese Option hat keine Wirkung, wenn das RAW-Format definiert ist. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnail4resource/minimalversion/) { get; } | Liest die minimal erforderliche PSD-Version. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-Zeichenkette, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0). |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | Liest oder setzt die Anzahl der Ebenen. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten ab. |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | Liest oder setzt die Größe nach Komprimierung. Wird für Konsistenzprüfungen verwendet. |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | Liest oder setzt die 32‑Bit‑ARGB-Thumbnail-Daten. |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | Liest oder setzt die Thumbnail-Daten. |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | Liest die gesamte Datenmenge. |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | Liest oder setzt die Breite des Thumbnails in Pixeln. |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | Liest die Zeilenbreite in Bytes. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock in den angegebenen Stream. |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | Validiert die Ressourcenwerte. |

### Siehe auch

* class [ThumbnailResource](../thumbnailresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


