---
title: "FileStreamContainer"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مساعد لمعالجة تدفق الملفات."
type: docs
weight: 44
url: /ar/java/com.aspose.psd/filestreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

مساعد لمعالجة تدفق الملفات.
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
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | ينشئ دفق ملف جديد. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتاً إلى الجهاز الأساسي. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getFilePath()](#getFilePath--) | يحصل على مسار الملف. |
| [getLength()](#getLength--) | يحصل على أو يضبط طول التدفق بالبايت. |
| [getPosition()](#getPosition--) | يحصل أو يعيّن الموضع الحالي داخل الدفق. |
| [getStream()](#getStream--) | يحصل على دفق البيانات. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
| [hashCode()](#hashCode--) |  |
| [isCreated()](#isCreated--) | يحصل على قيمة تشير إلى ما إذا تم إنشاء الدفق صراحةً. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق يتم التخلص منه عند الإغلاق. |
| [isTemporal()](#isTemporal--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الدفق مؤقتًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | يفتح دفق ملف موجود. |
| [openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)](#openFileStream-internalized-java.lang.String-boolean-) | يفتح دفق ملف موجود. |
| [read(byte[] bytes)](#read-byte---) | يقرأ البايتات لملء المخزن المؤقت للبايتات المحدد. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | يقرأ تسلسلًا من البايتات من الدفق الحالي ويقدّم الموضع داخل الدفق بعدد البايتات المقروءة. |
| [readByte()](#readByte--) | يقرأ بايتًا من الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath)](#save-java.lang.String-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [seek(long offset, int origin)](#seek-long-int-) | يضبط الموضع داخل الدفق الحالي. |
| [seekBegin()](#seekBegin--) | يضبط موضع الدفق إلى بداية الدفق. |
| [setLength(long value)](#setLength-long-) | يحصل على أو يضبط طول التدفق بالبايت. |
| [setPosition(long value)](#setPosition-long-) | يحصل أو يعيّن الموضع الحالي داخل الدفق. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الدفق مؤقتًا. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | يحوّل بيانات الدفق إلى مصفوفة الـ byte. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | يحوّل بيانات الدفق إلى مصفوفة الـ byte. |
| [toString()](#toString--) |  |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.psd.FileStreamContainer-) | يُجري تحويلًا صريحًا من [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) إلى FileInputStream. |
| [to_FileStream_internalized(FileStreamContainer fileStreamContainer)](#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.psd.FileStreamContainer-) | يُجري تحويلًا صريحًا من [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) إلى java.io.InputStream. |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | يُجري تحويلًا صريحًا من  com.aspose.imaging.StreamContainer  إلى  System.IO.Stream . |
| [to_Stream_internalized(FileStreamContainer fileStreamContainer)](#to-Stream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | يكتب جميع البايتات المحددة إلى الدفق. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| [writeByte(byte value)](#writeByte-byte-) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | ينسخ البيانات المحتواة إلى StreamContainer آخر. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | ينسخ البيانات المحتواة إلى StreamContainer آخر. |
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

### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


ينشئ دفق ملف جديد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileLocation | java.lang.String | موقع الملف. |
| isTemporal | boolean | إذا تم تعيينه إلى  true  فإن حاوية دفق الملف تكون مؤقتة. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
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
### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


يحصل على مسار الملف.

القيمة: مسار الملف.

**Returns:**
java.lang.String
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
### isCreated() {#isCreated--}
```
public final boolean isCreated()
```


يحصل على قيمة تشير إلى ما إذا تم إنشاء الدفق صراحةً.

القيمة:  true  إذا تم إنشاء الدفق صراحةً؛ وإلا،  false .

**Returns:**
boolean
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الدفق يتم التخلص منه عند الإغلاق.

القيمة:  true  إذا تم التخلص من الدفق عند الإغلاق؛ وإلا،  false .

**Returns:**
boolean
### isTemporal() {#isTemporal--}
```
public final boolean isTemporal()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الدفق مؤقتًا.

القيمة:  true  إذا كان الدفق مؤقتًا؛ وإلا،  false .

--------------------

سيقوم الدفق المؤقت بإزالة نفسه عند التخلص منه. إذا كان الدفق قائمًا على الذاكرة، فإن هذه الخاصية لا تأثير لها. يمكن وضع علامة على الدفق كـ مؤقت أو دائم في حال تم إنشاؤه صراحةً وإلا سيتم رمي الاستثناء المناسب.

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




### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


يفتح دفق ملف موجود. إذا لم يكن دفق الملف موجودًا يتم رمي الاستثناء المناسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileLocation | java.lang.String | موقع الملف. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams) {#openFileStream-internalized-java.lang.String-boolean-}
```
public static FileStreamContainer openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)
```


يفتح دفق ملف موجود. إذا لم يكن دفق الملف موجودًا يتم رمي الاستثناء المناسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileLocation | java.lang.String | موقع الملف. |
| disposeDuplicatedStreams | boolean | إذا تم تعيينه إلى  true  يتم التخلص من التدفقات المكررة. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
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

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | الدفق لحفظ البيانات إليه. |
| bufferSize | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة  ReadWriteBytesCount . |
| length | long | طول بيانات الدفق للنسخ. بشكل افتراضي يتم تعيين الطول إلى قيمة Length. |

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

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


يضبط الموضع داخل الدفق الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الإزاحة | long | إزاحة بايت نسبية إلى معلمة origin. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الممرر في مُنشئ StreamContainer. |
| origin | int | قيمة من النوع  System.IO.SeekOrigin  تشير إلى نقطة المرجع المستخدمة للحصول على الموضع الجديد. |

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

### setTemporal(boolean value) {#setTemporal-boolean-}
```
public final void setTemporal(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الدفق مؤقتًا.

القيمة:  true  إذا كان الدفق مؤقتًا؛ وإلا،  false .

--------------------

سيقوم الدفق المؤقت بإزالة نفسه عند التخلص منه. إذا كان الدفق قائمًا على الذاكرة، فإن هذه الخاصية لا تأثير لها. يمكن وضع علامة على الدفق كـ مؤقت أو دائم في حال تم إنشاؤه صراحةً وإلا سيتم رمي الاستثناء المناسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.psd.FileStreamContainer-}
```
public static FileInputStream to_FileStream(FileStreamContainer fileStreamContainer)
```


يُجري تحويلًا صريحًا من [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) إلى FileInputStream.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | حاوية دفق الملف. |

**Returns:**
java.io.FileInputStream - نتيجة التحويل.
### to_FileStream_internalized(FileStreamContainer fileStreamContainer) {#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.FileStream
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.psd.FileStreamContainer-}
```
public static InputStream to_Stream(FileStreamContainer fileStreamContainer)
```


يُجري تحويلًا صريحًا من [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) إلى java.io.InputStream.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | حاوية دفق الملف. |

**Returns:**
java.io.InputStream - نتيجة التحويل.
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
### to_Stream_internalized(FileStreamContainer fileStreamContainer) {#to-Stream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.Stream to_Stream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.Stream
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

