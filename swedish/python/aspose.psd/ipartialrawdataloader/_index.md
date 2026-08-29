---
title: "IPartialRawDataLoader klass"
type: docs
weight: 1940
url: /sv/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Bearbetar den laddade datan. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Bearbetar den laddade datan. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Bearbetar den laddade datan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Daterektangeln. |
| data | byte | Den råa datan. |
| start | [Point](/psd/python-net/aspose.psd/point) | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](/psd/python-net/aspose.psd/point) | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Bearbetar den laddade datan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Daterektangeln. |
| data | byte | Den råa datan. |
| start | [Point](/psd/python-net/aspose.psd/point) | Startdatapunkten. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](/psd/python-net/aspose.psd/point) | Slutdatapunkten. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

