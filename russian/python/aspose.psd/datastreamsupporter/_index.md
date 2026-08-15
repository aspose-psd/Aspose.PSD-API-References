---
title: "Класс DataStreamSupporter"
type: docs
weight: 1030
url: /ru/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Получает поток данных объекта. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| закешировано | bool | r | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется чтение данных. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| cache_data() | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) не будет выполнена. |
| save() | Сохраняет данные объекта в текущий [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Сохраняет данные объекта в указанное расположение файла. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_3) | Сохраняет данные объекта в указанный поток. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |
| over_write | bool | если установить в <c>true</c>, содержимое файла будет перезаписано, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных объекта. |

