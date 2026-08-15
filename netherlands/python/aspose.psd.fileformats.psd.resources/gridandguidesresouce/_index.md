---
title: "GridAndGuidesResouce Klasse"
type: docs
weight: 110
url: /nl/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Initialiseert een nieuw exemplaar van de GridAndGuidesResouce klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | De resourcesignatuur van ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | De reguliere Photoshop-resourcesignatuur. |
| data_size | int | r | Haalt de grootte van de resourcegegevens op in bytes. |
| grid_cycle_x | int | r/w | Haalt of stelt de horizontale rastercyclus in. Standaard is 576. |
| grid_cycle_y | int | r/w | Haalt of stelt de verticale rastercyclus in. Standaard is 576. |
| guide_count | int | r | Haalt het aantal gidsresourceblokken op. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Haalt of stelt de gidsen in. |
| header_version | int | r/w | Haalt of stelt de headerversie in. Deze waarde moet altijd 1 zijn. |
| id | short | r/w | Haalt de unieke identifier van de resource op of stelt deze in. |
| minimal_version | int | r | Haalt de minimaal vereiste psd‑versie op. |
| name | string | r/w | Haalt de resource‑naam op of stelt deze in. Pascal‑string, opgevuld om de grootte even te maken (een nul‑naam bestaat uit twee bytes van 0). |
| signature | int | r | Haalt de resourcesignatuur op. Zou altijd '8BIM' moeten zijn. |
| grootte | int | r | Haalt de grootte van het resource‑blok op in bytes, inclusief de gegevens. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream)](#save_stream_1) | Slaat het resource‑blok op in de opgegeven stream. |
| validate_values() | Valideert de resource‑waarden. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Initialiseert een nieuw exemplaar van de GridAndGuidesResouce klasse

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Slaat het resource‑blok op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De stream waarin het resource‑blok moet worden opgeslagen. |

