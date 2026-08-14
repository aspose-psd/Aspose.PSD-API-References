---
title: "Classe DataStreamSupporter"
type: docs
weight: 1030
url: /it/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Ottiene lo stream di dati dell'oggetto. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| è_in_cache | bool | r | Ottiene un valore che indica se i dati dell'oggetto sono attualmente nella cache e non è necessaria la lettura dei dati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Memorizza nella cache i dati e garantisce che non vengano caricati dati aggiuntivi dal sottostante [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| save() | Salva i dati dell'oggetto nel corrente [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(stream)](#save_stream_3) | Salva i dati dell'oggetto nello stream specificato. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |
| over_write | bool | se impostato su <c>true</c> sovrascrive il contenuto del file, altrimenti verrà eseguita un'aggiunta. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Salva i dati dell'oggetto nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Il flusso in cui salvare i dati dell'oggetto. |

