---
title: "SplitStreamContainer"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق."
type: docs
weight: 102
url: /ar/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | يُنشئ مثلاً جديداً من الفئة [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | يُنشئ مثلاً جديداً من الفئة [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | يُنشئ مثلاً جديداً من الفئة [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canRead()](#canRead--) | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| [canSeek()](#canSeek--) | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم التنقل. |
| [canWrite()](#canWrite--) | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتاً إلى الجهاز الأساسي. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getLength()](#getLength--) | يحصل على أو يضبط طول التدفق بالبايت. |
| [getPosition()](#getPosition--) | يحصل أو يعيّن الموضع الحالي داخل الدفق. |
| [getStream()](#getStream--) | يحصل على دفق البيانات. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | يدرج حاوية الدفق في الموضع المحدد. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق يتم التخلص منه عند الإغلاق. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | يقرأ البايتات لملء المخزن المؤقت للبايتات المحدد. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | يقرأ تسلسلًا من البايتات من الدفق الحالي ويقدّم الموضع داخل الدفق بعدد البايتات المقروءة. |
| [readByte()](#readByte--) | يقرأ بايتًا من الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath)](#save-java.lang.String-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | يضبط الموضع داخل الدفق الحالي. |
| [seekBegin()](#seekBegin--) | يضبط موضع الدفق إلى بداية الدفق. |
| [setLength(long value)](#setLength-long-) | يحصل على أو يضبط طول التدفق بالبايت. |
| [setPosition(long value)](#setPosition-long-) | يحصل أو يعيّن الموضع الحالي داخل الدفق. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | يحوّل بيانات الدفق إلى مصفوفة الـ byte. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | يحوّل بيانات الدفق إلى مصفوفة الـ byte. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | يُجري تحويلًا صريحًا من  com.aspose.imaging.StreamContainer  إلى  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | يكتب جميع البايتات المحددة إلى الدفق. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| [writeByte(byte value)](#writeByte-byte-) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | ينسخ البيانات المحتواة إلى StreamContainer آخر. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | ينسخ البيانات المحتواة إلى StreamContainer آخر. |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


يُنشئ مثلاً جديداً من الفئة [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | التدفق. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


يُنشئ مثلاً جديداً من الفئة [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق البيانات. |
| disposeStream | boolean | إذا تم تعيينه إلى  true  سيتم التخلص من الدفق عندما يتم التخلص من الحاوية. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


يُنشئ مثلاً جديداً من الفئة [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| disposeStream | boolean | إذا تم تعيينه إلى  true  يتخلص من الدفق. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة.

### canRead() {#canRead--}
```
public boolean canRead()
```


يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة.

القيمة:  true  إذا كان الدفق يدعم القراءة؛ وإلا،  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم التنقل.

القيمة:  true  إذا كان الدفق يدعم السعي؛ وإلا،  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة.

القيمة:  true  إذا كان الدفق يدعم الكتابة؛ وإلا،  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

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
### flush() {#flush--}
```
public void flush()
```


يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتاً إلى الجهاز الأساسي.

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getLength() {#getLength--}
```
public long getLength()
```


يحصل أو يضبط طول الدفق بالبايتات. هذه القيمة أقل من  System.IO.Stream.Length  بمقدار موضع بدء الدفق الممرّر في مُنشئ StreamContainer.

القيمة: طول الدفق.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


يحصل أو يعيّن الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الذي تم تمريره في مُنشئ StreamContainer.

القيمة: موضع الدفق الحالي.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


يحصل على دفق البيانات.

القيمة: دفق البيانات.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
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
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


يدرج حاوية الدفق في الموضع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | int | الموضع للإدراج فيه. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق للإدراج. |
| disposeStream | boolean | إذا تم تعيينه إلى  true  يتخلص من الدفق. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الدفق يتم التخلص منه عند الإغلاق.

القيمة:  true  إذا تم التخلص من الدفق عند الإغلاق؛ وإلا،  false .

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




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


يقرأ البايتات لملء المخزن المؤقت للبايتات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات للتعبئة. |

**Returns:**
int - عدد البايتات المقروءة. قد تكون هذه القيمة أقل من عدد البايتات في المخزن المؤقت إذا لم يتوفر عدد كافٍ من البايتات في الدفق.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


يقرأ تسلسلًا من البايتات من الدفق الحالي ويقدّم الموضع داخل الدفق بعدد البايتات المقروءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | byte[] | مصفوفة من البايتات. عند عودة هذه الطريقة، يحتوي المخزن المؤقت على مصفوفة البايتات المحددة مع القيم بين  offset  و ( offset  +  count  - 1) المستبدلة بالبايتات المقروءة من المصدر الحالي. |
| الإزاحة | int | الإزاحة الصفرية للبايت في  buffer  التي يبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| count | int | الحد الأقصى لعدد البايتات التي سيتم قراءتها من الدفق الحالي. |

**Returns:**
int - إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. قد تكون هذه أقل من عدد البايتات المطلوبة إذا لم تتوفر تلك البايتات حاليًا، أو صفر (0) إذا تم الوصول إلى نهاية الدفق.
### readByte() {#readByte--}
```
public int readByte()
```


يقرأ بايتًا من الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق.

**Returns:**
int - البايت غير الموقع محوّل إلى Int32، أو -1 إذا كان عند نهاية الدفق.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي  ReadWriteBytesCount  وقيمة الدفق  Length .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | الدفق لحفظ البيانات إليه. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


يحفظ (ينسخ) كل بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق  Length .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | الدفق لحفظ البيانات إليه. |
| bufferSize | int | المخزن المؤقت. |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dstStream | java.io.OutputStream | الدفق لحفظ البيانات إليه. |
| bufferSize | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT). |
| length | long | طول بيانات الدفق للنسخ. بشكل افتراضي يتم تعيين الطول إلى قيمة  Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)). |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي  ReadWriteBytesCount  وقيمة الدفق  Length .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الدفق إليه. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق  Length .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الدفق إليه. |
| bufferSize | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة  ReadWriteBytesCount . |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الدفق إليه. |
| bufferSize | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة  ReadWriteBytesCount . |
| length | long | طول بيانات الدفق للنسخ. بشكل افتراضي يتم تعيين الطول إلى قيمة Length. |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| length | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


يضبط الموضع داخل الدفق الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الإزاحة | long | إزاحة بايت نسبية إلى معلمة origin. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الممرر في مُنشئ StreamContainer. |
| origin | int | قيمة من النوع [SeekOrigin](../../com.aspose.psd/seekorigin) تشير إلى نقطة المرجع المستخدمة للحصول على الموضع الجديد. |

**Returns:**
long - الموضع الجديد داخل الدفق الحالي.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


يضبط موضع الدفق إلى بداية الدفق. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الممرر في مُنشئ StreamContainer.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


يحصل أو يضبط طول الدفق بالبايتات. هذه القيمة أقل من  System.IO.Stream.Length  بمقدار موضع بدء الدفق الممرّر في مُنشئ StreamContainer.

القيمة: طول الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


يحصل أو يعيّن الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الذي تم تمريره في مُنشئ StreamContainer.

القيمة: موضع الدفق الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


يحوّل بيانات الدفق إلى مصفوفة الـ byte.

**Returns:**
byte[] - بيانات الدفق محوَّلة إلى مصفوفة byte.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


يحوّل بيانات الدفق إلى مصفوفة الـ byte.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع لبدء قراءة البايتات منه. |
| bytesCount | long | عدد البايتات للقراءة. |

**Returns:**
byte[] - بيانات الدفق محوَّلة إلى مصفوفة byte.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


يُجري تحويلًا صريحًا من  com.aspose.imaging.StreamContainer  إلى  System.IO.Stream .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |

**Returns:**
com.aspose.ms.System.IO.Stream - نتيجة التحويل.
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


يكتب جميع البايتات المحددة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات للكتابة. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | byte[] | مصفوفة من البايتات. تقوم هذه الطريقة بنسخ count بايت من buffer إلى الدفق الحالي. |
| الإزاحة | int | إزاحة البايت الصفرية في buffer التي يبدأ عندها نسخ البايتات إلى الدفق الحالي. |
| count | int | عدد البايتات التي ستُكتب إلى الدفق الحالي. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | البايت للكتابة إلى الدفق. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


ينسخ البيانات المحتواة إلى StreamContainer آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق للنسخ إليها. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


ينسخ البيانات المحتواة إلى StreamContainer آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق للنسخ إليها. |
| length | long | عدد البايتات للكتابة. |

