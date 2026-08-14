---
title: "ThumbnailResource Klasse"
type: docs
weight: 250
url: /de/python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | Initialisiert eine neue Instanz der ThumbnailResource Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Die Ressourcensignatur von ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Die reguläre Photoshop‑Ressourcensignatur. |
| bits_pixel | short | r/w | Ruft die Bits pro Pixel ab oder legt sie fest. |
| data_size | int | r | Gibt die Größe der Ressourcendaten in Bytes zurück. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Ruft das Datenformat des Thumbnails ab oder legt es fest. |
| height | int | r/w | Ruft die Höhe des Thumbnails in Pixeln ab oder legt sie fest. |
| id | short | r/w | Liest oder setzt die eindeutige Kennung für die Ressource. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Ruft die JPEG-Optionen ab. Geeignet, wenn die Thumbnail-Ressource ausschließlich im JPEG-Dateiformat gespeichert wird. Diese Option hat keine Wirkung, wenn das RAW-Format definiert ist. |
| minimal_version | int | r | Ruft die minimal erforderliche PSD-Version ab. |
| name | string | r/w | Liest oder setzt den Ressourcennamen. Pascal-String, aufgefüllt, damit die Größe gerade ist (ein Nullname besteht aus zwei Bytes mit 0). |
| planes_count | short | r/w | Ruft die Anzahl der Ebenen ab oder legt sie fest. |
| signature | int | r | Liefert die Ressourcensignatur. Sollte immer '8BIM' sein. |
| Größe | int | r | Liefert die Blockgröße der Ressource in Bytes einschließlich ihrer Daten. |
| size_after_compression | int | r | Ruft die Größe nach der Kompression ab oder legt sie fest. Wird zur Konsistenzprüfung verwendet. |
| thumbnail_argb_32_data | int | r/w | Liest oder setzt die 32‑Bit‑ARGB‑Vorschaudaten. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt die Vorschaudaten. |
| total_size | int | r | Liest die Gesamtdatengröße. |
| width | int | r/w | Liest oder setzt die Breite der Vorschau in Pixeln. |
| width_bytes | int | r | Liest die Zeilenbreite in Bytes. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream)](#save_stream_1) | Speichert die Ressourcenblockdaten. |
| validate_values() | Validiert die Ressourcenwerte. |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

Initialisiert eine neue Instanz der ThumbnailResource Klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Speichert die Ressourcenblockdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

