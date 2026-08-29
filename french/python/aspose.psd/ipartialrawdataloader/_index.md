---
title: "IPartialRawDataLoader Classe"
type: docs
weight: 1940
url: /fr/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Traite les données chargées. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Traite les données chargées. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Traite les données chargées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle de données. |
| data | byte | Les données brutes. |
| start | [Point](/psd/python-net/aspose.psd/point) | Le point de données de départ. S'il n'est pas égal à (left,top), cela signifie que ce n'est pas un rectangle complet. |
| end | [Point](/psd/python-net/aspose.psd/point) | Le point de données final. S'il n'est pas égal à (right,bottom), cela signifie que ce n'est pas un rectangle complet. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Traite les données chargées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle de données. |
| data | byte | Les données brutes. |
| start | [Point](/psd/python-net/aspose.psd/point) | Le point de données de départ. S'il n'est pas égal à (left,top), cela signifie que ce n'est pas un rectangle complet. |
| end | [Point](/psd/python-net/aspose.psd/point) | Le point de données final. S'il n'est pas égal à (right,bottom), cela signifie que ce n'est pas un rectangle complet. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Les options de chargement. |

