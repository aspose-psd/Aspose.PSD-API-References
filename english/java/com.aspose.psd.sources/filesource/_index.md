---
title: FileSource
second_title: Aspose.PSD for Java API Reference
description: Represents a file source which is capable of files manipulation.
type: docs
weight: 12
url: /java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

Represents a file source which is capable of files manipulation.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | Gets the stream container. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Gets a value indicating whether file will be temporal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSource() {#FileSource--}
```
public FileSource()
```


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
### getStreamContainer() {#getStreamContainer--}
```
public abstract StreamContainer getStreamContainer()
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
public abstract boolean isTemporal()
```


Gets a value indicating whether file will be temporal.

**Returns:**
boolean -  true  if file will be temporal; otherwise,  false .
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

