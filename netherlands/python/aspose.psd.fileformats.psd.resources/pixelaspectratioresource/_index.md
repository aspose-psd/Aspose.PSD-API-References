---
title: "PixelAspectRatioResource Klasse"
type: docs
weight: 190
url: /nl/python-net/aspose.psd.fileformats.psd.resources/pixelaspectratioresource/
---

**Summary:** Pixel aspect ration resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.PixelAspectRatioResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PixelAspectRatioResource()](#PixelAspectRatioResource__1) | Initialiseert een nieuw exemplaar van de PixelAspectRatioResource klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | De resourcesignatuur van ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | De reguliere Photoshop-resourcesignatuur. |
| aspect_ratio | double | r/w | Haalt de beeldverhouding op of stelt deze in. |
| data_size | int | r | Haalt de grootte van de resourcegegevens op in bytes. |
| id | short | r/w | Haalt de unieke identifier van de resource op of stelt deze in. |
| minimal_version | int | r | Haalt de minimaal vereiste PSD-versie op. |
| name | string | r/w | Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een nul‑naam bestaat uit twee bytes van 0). |
| signature | int | r | Haalt de resourcesignatuur op. Zou altijd '8BIM' moeten zijn. |
| grootte | int | r | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
| version | int | r/w | Haalt de versie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream)](#save_stream_1) | Slaat het resource‑blok op in de opgegeven stream. |
| validate_values() | Valideert de resource‑waarden. |


### Constructor: PixelAspectRatioResource() {#PixelAspectRatioResource__1}


```
 PixelAspectRatioResource() 
```

Initialiseert een nieuw exemplaar van de PixelAspectRatioResource klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Slaat het resource‑blok op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De stream waarin het resource‑blok moet worden opgeslagen. |

