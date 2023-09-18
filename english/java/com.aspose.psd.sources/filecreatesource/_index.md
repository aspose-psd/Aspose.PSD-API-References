---
title: FileCreateSource
second_title: Aspose.PSD for Java API Reference
description: Represents a file source for creation.
type: docs
weight: 10
url: /java/com.aspose.psd.sources/filecreatesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Represents a file source for creation.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Initializes a new instance of the  FileCreateSource  class. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Initializes a new instance of the  FileCreateSource  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Gets the file path to create. |
| [getStreamContainer()](#getStreamContainer--) | Gets the stream container. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Gets a value indicating whether file will be temporal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Initializes a new instance of the  FileCreateSource  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to create. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Initializes a new instance of the  FileCreateSource  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to create. |
| isTemporal | boolean | If set to  true  the created file will be temporal. |

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
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Gets the file path to create.

Value: The file path to create.

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Gets the stream container.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

Use with caution. You will need to dispose the stream container after retrieval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Gets a value indicating whether file will be temporal.

Value:  true  if file will be temporal; otherwise,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

