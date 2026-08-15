---
title: "Thumbnail4Resource Klasse"
type: docs
weight: 240
url: /nl/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | Initialiseert een nieuw exemplaar van de Thumbnail4Resource klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | De resourcesignatuur van ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | De reguliere Photoshop-resourcesignatuur. |
| bits_pixel | short | r/w | Haalt de bits per pixel op of stelt deze in. |
| data_size | int | r | Haalt de grootte van de resourcegegevens op in bytes. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Haalt het thumbnail-gegevensformaat op of stelt dit in. |
| hoogte | int | r/w | Haalt de hoogte van de thumbnail in pixels op of stelt deze in. |
| id | short | r/w | Haalt de unieke identifier van de resource op of stelt deze in. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Haalt de JPEG-opties op en stelt ze in. Geschikt wanneer de thumbnailresource alleen wordt opgeslagen in JPEG-bestandsformaat. Deze optie heeft geen effect wanneer RAW-formaat is gedefinieerd. |
| minimal_version | int | r | Haalt de minimaal vereiste psd‑versie op. |
| name | string | r/w | Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een nul‑naam bestaat uit twee bytes van 0). |
| planes_count | short | r/w | Haalt of stelt het aantal vlakken in. |
| signature | int | r | Haalt de resourcesignatuur op. Zou altijd '8BIM' moeten zijn. |
| grootte | int | r | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
| size_after_compression | int | r | Haalt of stelt de grootte na compressie in. Wordt gebruikt voor consistentiecontrole. |
| thumbnail_argb_32_data | int | r/w | Haalt of stelt de 32‑bit ARGB‑miniatuurgegevens in. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Haalt of stelt de miniatuurgegevens in. |
| total_size | int | r | Haalt de totale gegevensgrootte op. |
| width | int | r/w | Haalt of stelt de breedte van de miniatuur in pixels in. |
| width_bytes | int | r | Haalt de rijbreedte in bytes op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream)](#save_stream_1) | Slaat de resourceblokgegevens op. |
| validate_values() | Valideert de resource‑waarden. |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

Initialiseert een nieuw exemplaar van de Thumbnail4Resource klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Slaat de resourceblokgegevens op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

