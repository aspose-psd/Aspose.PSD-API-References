---
title: "IPartialRawDataLoader Klasse"
type: docs
weight: 1940
url: /de/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Verarbeitet die geladenen Daten. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Verarbeitet die geladenen Daten. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Verarbeitet die geladenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Datenrechteck. |
| data | byte | Die Rohdaten. |
| start | [Point](/psd/python-net/aspose.psd/point) | Der Startdatenpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](/psd/python-net/aspose.psd/point) | Der Enddatenpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Verarbeitet die geladenen Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Datenrechteck. |
| data | byte | Die Rohdaten. |
| start | [Point](/psd/python-net/aspose.psd/point) | Der Startdatenpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](/psd/python-net/aspose.psd/point) | Der Enddatenpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Die Ladeoptionen. |

