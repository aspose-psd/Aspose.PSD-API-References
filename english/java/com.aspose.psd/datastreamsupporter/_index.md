---
title: DataStreamSupporter
second_title: Aspose.PSD for Java API Reference
description: The data stream container.
type: docs
weight: 38
url: /java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

The data stream container.
## Fields

| Field | Description |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Occurs when image was loaded or saved |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Occurs when credit was used |
## Methods

| Method | Description |
| --- | --- |
| [cacheData()](#cacheData--) | Caches the data and ensures no additional data loading will be performed from the underlying  DataStreamSupporter.DataStreamContainer . |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [dispose()](#dispose--) | Disposes the current instance. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Gets the object's data stream. |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Gets the file path of source image if it's exist. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Gets a value indicating whether object uses memory optimization strategy |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Saves the object's data to the current  DataStreamSupporter . |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the object's data to the specified stream. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Saves the object's data to the specified stream. |
| [save(String filePath)](#save-java.lang.String-) | Saves the object's data to the specified file location. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Saves the object's data to the specified file location. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Sets the object's data stream. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Sets a value indicating whether [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Occurs when image was loaded or saved

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Occurs when credit was used

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Caches the data and ensures no additional data loading will be performed from the underlying  DataStreamSupporter.DataStreamContainer .

### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the current instance.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the object's data stream.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Gets the file path of source image if it's exist. Returns an empty string if can't find the source path.

**Returns:**
java.lang.String - The file path of source image.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Gets a value indicating whether object uses memory optimization strategy

Value:  true  if object uses memory optimization strategy; otherwise,  false .

**Returns:**
boolean - a value indicating whether object uses memory optimization strategy
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


Gets a value indicating whether object's data is cached currently and no data reading is required.

**Returns:**
boolean - a value indicating whether object's data is cached currently and no data reading is required.
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


Saves the object's data to the current  DataStreamSupporter .

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the object's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save the object's data to. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Saves the object's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.io.RandomAccessFile | The stream to save the object's data to. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Saves the object's data to the specified file location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the object's data to. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Saves the object's data to the specified file location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the object's data to. |
| overWrite | boolean | if set to  true  over write the file contents, otherwise append will occur. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Sets the object's data stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | The object's data stream. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Sets a value indicating whether [ignore after save].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if [ignore after save]; otherwise,  false . |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

