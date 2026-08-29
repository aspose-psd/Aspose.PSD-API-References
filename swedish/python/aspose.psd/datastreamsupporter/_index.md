---
title: "DataStreamSupporter-klass"
type: docs
weight: 1030
url: /sv/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Hämtar objektets datastream. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| is_cached | bool | r | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| cache_data() | Cachar data och säkerställer att ingen ytterligare datainläsning utförs från den underliggande [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| save() | Sparar objektets data till den aktuella [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Sparar objektets data till den angivna filplatsen. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Sparar objektets data till den angivna filplatsen. |
| [save(stream)](#save_stream_3) | Sparar objektets data till den angivna strömmen. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filens innehåll, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara objektets data till. |

