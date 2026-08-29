---
title: "DataStreamSupporter"
second_title: "Aspose.PSD for Java API Справочник"
description: "Контейнер потока данных."
type: docs
weight: 38
url: /ru/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Контейнер потока данных.
## Поля

| Поле | Описание |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Происходит, когда изображение загружено или сохранено |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Происходит, когда кредит был использован |
## Методы

| Метод | Описание |
| --- | --- |
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового DataStreamSupporter.DataStreamContainer не будет выполнена. |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Получает поток данных объекта. |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Получает путь к файлу исходного изображения, если он существует. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Получает значение, указывающее, использует ли объект стратегию оптимизации памяти |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Сохраняет данные объекта в текущий  DataStreamSupporter . |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет данные объекта в указанный поток. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Сохраняет данные объекта в указанный поток. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет данные объекта в указанное файловое расположение. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Сохраняет данные объекта в указанное файловое расположение. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Устанавливает поток данных объекта. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Устанавливает значение, указывающее, следует ли [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Происходит, когда изображение загружено или сохранено

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Происходит, когда кредит был использован

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Кеширует данные и гарантирует, что дополнительная загрузка данных из базового DataStreamSupporter.DataStreamContainer не будет выполнена.

### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Получает поток данных объекта.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Получает путь к файлу исходного изображения, если он существует. Возвращает пустую строку, если не удаётся найти исходный путь.

**Returns:**
java.lang.String - Путь к файлу исходного изображения.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Получает значение, указывающее, использует ли объект стратегию оптимизации памяти

Значение:  true  если объект использует стратегию оптимизации памяти; иначе,  false .

**Returns:**
boolean - значение, указывающее, использует ли объект стратегию оптимизации памяти
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Возвращает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных.

**Returns:**
boolean — значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется ли чтение данных.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Сохраняет данные объекта в текущий  DataStreamSupporter .

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет данные объекта в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения данных объекта. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Сохраняет данные объекта в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файл | java.io.RandomAccessFile | Поток для сохранения данных объекта. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Сохраняет данные объекта в указанное файловое расположение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для сохранения данных объекта. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Сохраняет данные объекта в указанное файловое расположение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для сохранения данных объекта. |
| overWrite | boolean | если установлено в true, перезаписывает содержимое файла, иначе будет выполнено добавление. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Устанавливает поток данных объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Поток данных объекта. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Устанавливает значение, указывающее, следует ли [ignore after save].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true, если [ignore after save]; иначе false. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

