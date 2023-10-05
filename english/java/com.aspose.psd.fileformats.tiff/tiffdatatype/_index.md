---
title: TiffDataType
second_title: Aspose.PSD for Java API Reference
description: The tiff data type.
type: docs
weight: 10
url: /java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

The tiff data type.
## Methods

| Method | Description |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [deepClone()](#deepClone--) | Performs a deep clone of this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the count of elements. |
| [getDataSize()](#getDataSize--) | Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data). |
| [getId()](#getId--) | Gets tag id integer representation. |
| [getTagId()](#getTagId--) | Gets the tag id. |
| [getTagType()](#getTagType--) | Gets the tag type. |
| [getValue()](#getValue--) | Gets the value this data type contains. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Gets a value indicatind whether tag is private. |
| [isValid()](#isValid--) | Gets a value indicating whether tag data is valid. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Reads the tag data. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Sets the value this data type contains. |
| [toString()](#toString--) | Returns a  System.String  that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Writes the additional tag data. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Writes the tag data. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | An object to compare with this instance. |

**Returns:**
int - A 32-bit signed integer that indicates the relative order of the objects being compared. The return value has these meanings: Value Meaning Less than zero This instance is less than  obj . Zero This instance is equal to  obj . Greater than zero This instance is greater than  obj .
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Performs a deep clone of this instance.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).

**Returns:**
long - The additional data size in bytes.

This is the data bytes count aligned to word boundary.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Gets the count of elements.

**Returns:**
long - The count of elements.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Gets the additional data size in bytes (in case the 12 bytes is not enough to fit the tag data).

**Returns:**
long - The additional data size in bytes.

This is exact bytes count.
### getId() {#getId--}
```
public int getId()
```


Gets tag id integer representation.

**Returns:**
int - The tag id integer representation
### getTagId() {#getTagId--}
```
public int getTagId()
```


Gets the tag id.

**Returns:**
int - The tag id.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Gets the tag type.

**Returns:**
int - The tag type.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Gets the value this data type contains.

**Returns:**
java.lang.Object - The value.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Gets a value indicatind whether tag is private. Private tiff tags are tags with tag id over 32768.

**Returns:**
boolean -  true  if tag data is valid; otherwise,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored.

**Returns:**
boolean -  true  if tag data is valid; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Reads the tag data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | The data stream. |
| position | long | The tag position. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Sets the value this data type contains.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value. |

### toString() {#toString--}
```
public String toString()
```


Returns a  System.String  that represents this instance.

**Returns:**
java.lang.String - A  System.String  that represents this instance.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Writes the additional tag data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | The data stream. |

**Returns:**
long - The actual bytes written.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Writes the tag data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | The data stream. |
| additionalDataOffset | long | The offset to write additional data to. |

