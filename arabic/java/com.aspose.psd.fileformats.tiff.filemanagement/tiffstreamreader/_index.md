---
title: "TiffStreamReader"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تيار TIFF لمعالجة تنسيق ملف TIFF ذو النهاية الصغرى."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

تيار TIFF لمعالجة تنسيق ملف TIFF ذو النهاية الصغرى.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | ينشئ مثيلاً جديداً من فئة TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | ينشئ مثيلاً جديداً من فئة TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | ينشئ مثيلاً جديداً من فئة TiffStreamReader. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | ينشئ مثيلاً جديداً من فئة TiffStreamReader. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | يحصل على طول القارئ. |
| [getThrowExceptions()](#getThrowExceptions--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | يقرأ مصفوفة من قيم البايت من التدفق. |
| [readBytes(long position, long count)](#readBytes-long-long-) | يقرأ مصفوفة من قيم البايت غير الموقعة من التدفق. |
| [readDouble(long position)](#readDouble-long-) | اقرأ قيمة مزدوجة واحدة من التدفق. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | يقرأ مصفوفة من القيم المزدوجة من التدفق. |
| [readFloat(long position)](#readFloat-long-) | اقرأ قيمة عائمة واحدة من التدفق. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | يقرأ مصفوفة من قيم الفاصلة العائمة من الدفق. |
| [readRational(long position)](#readRational-long-) | يقرأ قيمة عدد كسرية واحدة من الدفق. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | يقرأ مصفوفة من القيم الكسرية من الدفق. |
| [readSByte(long position)](#readSByte-long-) | يقرأ بيانات بايت موقعة من الدفق. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | يقرأ مصفوفة من قيم البايت الموقعة من الدفق. |
| [readSLong(long position)](#readSLong-long-) | يقرأ قيمة عدد صحيح موقعة من الدفق. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من الدفق. |
| [readSRational(long position)](#readSRational-long-) | يقرأ قيمة عدد كسرية موقعة واحدة من الدفق. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | يقرأ مصفوفة من القيم الكسرية الموقعة من الدفق. |
| [readSShort(long position)](#readSShort-long-) | يقرأ قيمة عدد قصير موقعة من الدفق. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | يقرأ مصفوفة من قيم الأعداد القصيرة الموقعة من الدفق. |
| [readString_internalized(long position)](#readString-internalized-long-) | يقرأ السلسلة من الـ strea. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | يقرأ السلسلة من الـ strea. |
| [readULong(long position)](#readULong-long-) | يقرأ قيمة عدد صحيح غير موقعة من الدفق. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من الدفق. |
| [readUShort(long position)](#readUShort-long-) | يقرأ قيمة عدد قصير غير موقعة من الدفق. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من الدفق. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | يحوّل البيانات الأساسية إلى حاوية الدفق. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


ينشئ مثيلاً جديداً من فئة TiffStreamReader.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | بيانات مصفوفة البايت. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


ينشئ مثيلاً جديداً من فئة TiffStreamReader.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في البيانات. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


ينشئ مثيلاً جديداً من فئة TiffStreamReader.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في البيانات. |
| dataLength | int | طول البيانات. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


ينشئ مثيلاً جديداً من فئة TiffStreamReader.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |

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
### getLength() {#getLength--}
```
public long getLength()
```


يحصل على طول القارئ.

القيمة: طول القارئ.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق).

القيمة:  true  إذا تم رمي الاستثناءات عند معالجة البيانات غير الصحيحة؛ وإلا، يتم تجاهل حالات الخطأ بصمت.

**Returns:**
boolean
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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


يقرأ مصفوفة من قيم البايت من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مصفوفة | byte[] | المصفوفة للتعبئة. |
| arrayIndex | int | فهرس المصفوفة للبدء بوضع القيم فيه. |
| position | long | موضع الدفق للقراءة منه. |
| count | long | عدد العناصر للقراءة. |

**Returns:**
long - مصفوفة قيم البايت.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


يقرأ مصفوفة من قيم البايت غير الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
byte[] - مصفوفة قيم البايت غير الموقعة.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


اقرأ قيمة مزدوجة واحدة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
double - القيمة المزدوجة المفردة.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


يقرأ مصفوفة من القيم المزدوجة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
double[] - مصفوفة قيم مزدوجة.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


اقرأ قيمة عائمة واحدة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
float - القيمة العائمة المفردة.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


يقرأ مصفوفة من قيم الفاصلة العائمة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
float[] - مصفوفة قيم عائمة.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


يقرأ قيمة عدد كسرية واحدة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


يقرأ مصفوفة من القيم الكسرية من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - مصفوفة القيم النسبية.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


يقرأ بيانات بايت موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
byte - قيمة البايت الموقعة.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


يقرأ مصفوفة من قيم البايت الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
byte[] - مصفوفة قيم البايت الموقعة.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


يقرأ قيمة عدد صحيح موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
int - قيمة عدد صحيح موقعة.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
int[] - مصفوفة قيم عدد صحيح موقعة.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


يقرأ قيمة عدد كسرية موقعة واحدة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


يقرأ مصفوفة من القيم الكسرية الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - مصفوفة القيم النسبية الموقعة.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


يقرأ قيمة عدد قصير موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
short - قيمة قصير موقعة.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد القصيرة الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
short[] - مصفوفة قيم قصير موقعة.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


يقرأ السلسلة من الـ strea.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع. |

**Returns:**
java.lang.String - السلسلة.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


يقرأ السلسلة من الـ strea.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع. |
| length | long | الطول. |

**Returns:**
java.lang.String - السلسلة.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


يقرأ قيمة عدد صحيح غير موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
long - قيمة عدد صحيح غير موقع.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
long[] - مصفوفة من قيم الأعداد الصحيحة غير الموقعة.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


يقرأ قيمة عدد قصير غير موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
int - قيمة عدد قصير غير موقع.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
int[] - مصفوفة من قيم الأعداد الصحيحة غير الموقعة.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق).

القيمة:  true  إذا تم رمي الاستثناءات عند معالجة البيانات غير الصحيحة؛ وإلا، يتم تجاهل حالات الخطأ بصمت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


يحوّل البيانات الأساسية إلى حاوية الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startPosition | long | موضع البداية للبدء في التحويل من. |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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

