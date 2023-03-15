---
title: Class ThumbnailResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Resources.ThumbnailResource klas. Der ThumbnailRessourcenblock.
type: docs
weight: 3910
url: /de/net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---
## ThumbnailResource class

Der Thumbnail-Ressourcenblock.

```csharp
public class ThumbnailResource : ResourceBlock
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ThumbnailResource](thumbnailresource/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | Holt oder setzt die Bits Pixel. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | Ruft die Ressourcendatengröße in Byte ab. |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | Ruft das Thumbnail-Datenformat ab oder legt es fest. |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | Ruft die Höhe der Miniaturansicht in Pixel ab oder legt sie fest. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung für die Ressource ab oder legt sie fest. |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | Ruft die JPEG-Optionen ab oder setzt sie. Geeignet, wenn die Thumbnail-Ressource nur im JPEG-Dateiformat gespeichert wird. Diese Option hat keine Auswirkung, wenn das RAW-Format definiert ist. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnailresource/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-String, aufgefüllt, um die Größe gleichmäßig zu machen (ein Nullname besteht aus zwei Bytes von 0). |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | Ruft die Anzahl der Ebenen ab oder legt sie fest. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Ressourcenblockgröße in Byte ab, einschließlich seiner Daten. |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | Ruft die Größe nach der Komprimierung ab oder legt sie fest. Wird zur Konsistenzprüfung verwendet. |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | Ruft die 32-Bit-ARGB-Thumbnail-Daten ab oder legt sie fest. |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | Ruft die Thumbnail-Daten ab oder legt sie fest. |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | Ruft die Gesamtdatengröße ab. |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | Ruft die Breite der Miniaturansicht in Pixel ab oder legt sie fest. |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | Ruft die Zeilenbreite in Bytes ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock im angegebenen Stream. |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | Validiert die Ressourcenwerte. |

### Siehe auch

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Montage [Aspose.PSD](../../)


