---
title: "FileOpenSource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示用于打开的文件来源。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.sources/fileopensource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

表示用于打开的文件来源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | 初始化 FileOpenSource 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | 获取要打开的文件路径。 |
| [getStreamContainer()](#getStreamContainer--) | 获取 stream 容器。 |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | 获取指示文件是否为临时的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


初始化 FileOpenSource 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要打开的文件路径。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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


获取要打开的文件路径。

值：要打开的文件路径。

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


获取 stream 容器。

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

请谨慎使用。检索后您需要释放流容器。
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


获取指示文件是否为临时的值。

值：  true  如果文件将是临时的；否则为  false 。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

