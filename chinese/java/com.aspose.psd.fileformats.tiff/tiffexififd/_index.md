---
title: "TiffExifIfd"
second_title: "Aspose.PSD 的 Java API 参考"
description: "TIFF Exif 图像文件目录类。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

TIFF Exif 图像文件目录类。

封装指向 Exif IFD 的指针。兼容性方面，Exif IFD 与 TIFF 中指定的 IFD 结构相同。但通常情况下，它不包含如 TIFF 那样的图像数据。更多细节请参阅 http://www.exiv2.org/tags.html 和 http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | 初始化 TiffExifIfd 类的新实例。 |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | 初始化 TiffExifIfd 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | 获取或设置指向 EXIF IFD 的指针。 |
| [hasValue()](#hasValue--) | 获取一个值，指示此实例是否具有值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | 获取或设置指向 EXIF IFD 的指针。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


初始化 TiffExifIfd 类的新实例。

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


初始化 TiffExifIfd 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | ifdOffset | long | 指向 Exif IFD 的指针。 |

互操作性，Exif IFD 具有与 TIFF 中指定的 IFD 相同的结构。然而，通常情况下，它不像 TIFF 那样包含图像数据。 |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


获取或设置指向 EXIF IFD 的指针。

**Returns:**
long - 指向 EXIF IFD 的指针。
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


获取一个值，指示此实例是否具有值。

**Returns:**
boolean - 如果此实例有值则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


获取或设置指向 EXIF IFD 的指针。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 指向 EXIF IFD 的指针。 |

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

