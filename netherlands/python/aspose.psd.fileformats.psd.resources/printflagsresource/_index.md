---
title: "PrintFlagsResource Klasse"
type: docs
weight: 200
url: /nl/python-net/aspose.psd.fileformats.psd.resources/printflagsresource/
---

**Summary:** Print flags resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.PrintFlagsResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PrintFlagsResource()](#PrintFlagsResource__1) | Initialiseert een nieuw exemplaar van de PrintFlagsResource klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | De resourcesignatuur van ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | De reguliere Photoshop-resourcesignatuur. |
| bleed_scale | short | r/w | Haalt de bleed-schaal op of stelt deze in. |
| bleed_width | int | r/w | Haalt de breedte van de bleed op of stelt deze in. |
| center_crop_mark | byte | r/w | Haalt de centrale bijsnijdmarkering op of stelt deze in. |
| data_size | int | r | Haalt de grootte van de resourcegegevens op in bytes. |
| id | short | r/w | Haalt de unieke identifier van de resource op of stelt deze in. |
| minimal_version | int | r | Haalt de minimaal vereiste PSD-versie op. |
| name | string | r/w | Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een nul‑naam bestaat uit twee bytes van 0). |
| signature | int | r | Haalt de resourcesignatuur op. Zou altijd '8BIM' moeten zijn. |
| grootte | int | r | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
| version | short | r/w | Haalt de versie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream)](#save_stream_1) | Slaat het resource‑blok op in de opgegeven stream. |
| validate_values() | Valideert de resource‑waarden. |


### Constructor: PrintFlagsResource() {#PrintFlagsResource__1}


```
 PrintFlagsResource() 
```

Initialiseert een nieuw exemplaar van de PrintFlagsResource klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Slaat het resource‑blok op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De stream waarin het resource‑blok moet worden opgeslagen. |

