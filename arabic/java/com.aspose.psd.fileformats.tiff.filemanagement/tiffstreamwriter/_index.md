---
title: "TiffStreamWriter"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "كاتب تيار TIFF."
type: docs
weight: 11
url: /ar/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

كاتب تيار TIFF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | ينشئ مثالا جديدا من الفئة TiffStreamWriter. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | يحصل أو يحدد موضع الدفق. |
| [getSyncRoot()](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | يحصل أو يحدد موضع الدفق. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | يكتب البيانات المحددة. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | يكتب البيانات المحددة. |
| [writeDouble(double data)](#writeDouble-double-) | يكتب قيمة مزدوجة واحدة إلى الدفق. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | يكتب مصفوفة من القيم المزدوجة إلى الدفق. |
| [writeFloat(float data)](#writeFloat-float-) | يكتب قيمة عائمة واحدة إلى الدفق. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | يكتب مصفوفة من القيم العائمة إلى الدفق. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | يكتب قيمة عدد كسرية واحدة إلى الدفق. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | يكتب مصفوفة من القيم الكسرية غير الموقعة إلى الدفق. |
| [writeSByte(byte data)](#writeSByte-byte-) | يكتب قيمة بايت موقعة واحدة إلى الدفق. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | يكتب مصفوفة من قيم البايت الموقعة إلى الدفق. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | يكتب مصفوفة من القيم الصحيحة إلى الدفق. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | يكتب قيمة عدد كسرية موقعة واحدة إلى الدفق. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | يكتب مصفوفة من القيم الكسرية الموقعة إلى الدفق. |
| [writeSShort(short data)](#writeSShort-short-) | يكتب قيمة قصيرة واحدة إلى الدفق. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | يكتب مصفوفة من القيم القصيرة إلى الدفق. |
| [writeSlong(int data)](#writeSlong-int-) | يكتب قيمة صحيحة واحدة إلى الدفق. |
| [writeUByte(byte data)](#writeUByte-byte-) | يكتب قيمة بايت واحدة إلى الدفق. |
| [writeULong(long data)](#writeULong-long-) | يكتب قيمة عدد صحيح غير موقّع واحدة إلى الدفق. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | يكتب مصفوفة من القيم الصحيحة غير الموقعة إلى الدفق. |
| [writeUShort(int data)](#writeUShort-int-) | يكتب قيمة قصيرة غير موقعة واحدة إلى الدفق. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | يكتب مصفوفة من القيم القصيرة غير الموقعة إلى الدفق. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


ينشئ مثالا جديدا من الفئة TiffStreamWriter.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | كاتب الدفق. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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
### getPosition() {#getPosition--}
```
public long getPosition()
```


يحصل أو يحدد موضع الدفق.

القيمة: موضع الدفق.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن.

القيمة: الكائن الذي يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن.

**Returns:**
java.lang.Object
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




### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


يحصل أو يحدد موضع الدفق.

القيمة: موضع الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


يكتب البيانات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | البيانات للكتابة. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


يكتب البيانات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | البيانات للكتابة. |
| الإزاحة | int | إزاحة البيانات. |
| dataLength | int | طول البيانات للكتابة. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


يكتب قيمة مزدوجة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | double | القيمة للكتابة. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


يكتب مصفوفة من القيم المزدوجة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | double[] | المصفوفة للكتابة. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


يكتب قيمة عائمة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | float | القيمة للكتابة. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


يكتب مصفوفة من القيم العائمة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | float[] | المصفوفة للكتابة. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


يكتب قيمة عدد كسرية واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | القيمة للكتابة. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


يكتب مصفوفة من القيم الكسرية غير الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | المصفوفة للكتابة. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


يكتب قيمة بايت موقعة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte | القيمة للكتابة. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


يكتب مصفوفة من قيم البايت الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | المصفوفة للكتابة. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


يكتب مصفوفة من القيم الصحيحة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | int[] | المصفوفة للكتابة. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


يكتب قيمة عدد كسرية موقعة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | القيمة للكتابة. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


يكتب مصفوفة من القيم الكسرية الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | المصفوفة للكتابة. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


يكتب قيمة قصيرة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | short | القيمة للكتابة. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


يكتب مصفوفة من القيم القصيرة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | short[] | المصفوفة للكتابة. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


يكتب قيمة صحيحة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | int | القيمة للكتابة. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


يكتب قيمة بايت واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte | القيمة للكتابة. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


يكتب قيمة عدد صحيح غير موقّع واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | long | القيمة للكتابة. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


يكتب مصفوفة من القيم الصحيحة غير الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | long[] | المصفوفة للكتابة. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


يكتب قيمة قصيرة غير موقعة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | int | القيمة للكتابة. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


يكتب مصفوفة من القيم القصيرة غير الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | int[] | المصفوفة للكتابة. |

