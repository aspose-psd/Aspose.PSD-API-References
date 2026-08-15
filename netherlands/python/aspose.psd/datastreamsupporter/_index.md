---
title: "DataStreamSupporter-klasse"
type: docs
weight: 1030
url: /nl/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Haalt de gegevensstroom van het object op. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| is_cached | bool | r | Haalt een waarde op die aangeeft of de gegevens van het object momenteel in de cache staan en er geen gegevenslezen nodig is. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| cache_data() | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen van de onderliggende [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| save() | Slaat de gegevens van het object op in de huidige [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(stream)](#save_stream_3) | Slaat de gegevens van het object op in de opgegeven stream. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |
| over_write | bool | als ingesteld op <c>true</c> wordt de bestandsinhoud overschreven, anders wordt er toegevoegd. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van het object op te slaan. |

