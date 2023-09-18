---
title: TiffExifIfd
second_title: Aspose.PSD for Java API Reference
description: The TIFF Exif image file directory class.
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

The TIFF Exif image file directory class.

Incapsulates a pointer to the Exif IFD. Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF. See http://www.exiv2.org/tags.html and http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html for more details.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initializes a new instance of the  TiffExifIfd  class. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initializes a new instance of the  TiffExifIfd  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Gets or sets the pointer to EXIF IFD. |
| [hasValue()](#hasValue--) | Gets a value indicating whether this instance has value. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Gets or sets the pointer to EXIF IFD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initializes a new instance of the  TiffExifIfd  class.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initializes a new instance of the  TiffExifIfd  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ifdOffset | long | A pointer to the Exif IFD.

Interoperability, Exif IFD has the same structure as that of the IFD specified in TIFF. ordinarily, however, it does not contain image data as in the case of TIFF. |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


Gets or sets the pointer to EXIF IFD.

**Returns:**
long - The pointer to EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Gets a value indicating whether this instance has value.

**Returns:**
boolean -  true  if this instance has value; otherwise,  false .
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


Gets or sets the pointer to EXIF IFD.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The pointer to EXIF IFD. |

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

