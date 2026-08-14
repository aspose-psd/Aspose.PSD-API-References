---
title: "DataStreamSupporter Klasse"
type: docs
weight: 1030
url: /de/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Liest den Datenstrom des Objekts. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) durchgeführt werden. |
| save() | Speichert die Daten des Objekts im aktuellen [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(stream)](#save_stream_3) | Speichert die Objektdaten in den angegebenen Stream. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |
| over_write | bool | Wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden. |

