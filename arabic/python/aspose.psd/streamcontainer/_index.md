---
title: "فئة StreamContainer"
type: docs
weight: 4230
url: /ar/python-net/aspose.psd/streamcontainer/
---

**Summary:** Represents stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StreamContainer

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [StreamContainer(stream)](#StreamContainer_stream_1) | يقوم بإنشاء نسخة جديدة من الفئة [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [StreamContainer(stream, dispose_stream)](#StreamContainer_stream_dispose_stream_2) | يقوم بإنشاء نسخة جديدة من الفئة [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة. |
| can_read | bool | r | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| can_seek | bool | r | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم التنقل. |
| can_write | bool | r | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| is_stream_disposed_on_close | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| الطول | long | r/w | يحصل أو يضبط طول التدفق بالبايت. هذه القيمة أقل من الـ  بموقع بدء التدفق الممرر في مُنشئ StreamContainer. |
| position | long | r/w | يحصل أو يضبط الموضع الحالي داخل التدفق. هذه القيمة تمثل الإزاحة من موقع بدء التدفق الممرر في مُنشئ StreamContainer. |
| تدفق | _io.BufferedRandom | r | يحصل على تدفق البيانات. |
| sync_root | object | r | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| flush() | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| [read(buffer, offset, count)](#read_buffer_offset_count_1) | يقرأ تسلسلًا من البايتات من التدفق الحالي ويقدم الموضع داخل التدفق بعدد البايتات المقروءة. |
| [read(bytes)](#read_bytes_2) | يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد. |
| [read_byte()](#read_byte__3) | يقرأ بايتًا من التدفق ويقدم الموضع داخل التدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية التدفق. |
| [save(destination_stream)](#save_destination_stream_4) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) وقيمة [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_5) | يحفظ (ينسخ) جميع بيانات التدفق إلى التدفق المحدد. يستخدم قيمة [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_6) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| [save(file_path)](#save_file_path_7) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) وقيمة [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_8) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_9) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| [seek(offset, origin)](#seek_offset_origin_10) | يضبط الموضع داخل الدفق الحالي. |
| seek_begin() | يضبط موضع الدفق إلى بداية الدفق. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الممرّر في مُنشئ StreamContainer. |
| [to_bytes()](#to_bytes__11) | يحوّل بيانات الدفق إلى مصفوفة من نوع int. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_12) | يحوّل بيانات الدفق إلى مصفوفة من نوع int. |
| [write(buffer, offset, count)](#write_buffer_offset_count_13) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| [write(bytes)](#write_bytes_14) | يكتب جميع البايتات المحددة إلى الدفق. |
| [write_byte(value)](#write_byte_value_15) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا. |
| [write_to(stream_container)](#write_to_stream_container_16) | ينسخ البيانات المحتواة إلى [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) آخر. |
| [write_to(stream_container, length)](#write_to_stream_container_length_17) | ينسخ البيانات المحتواة إلى [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) آخر. |


### Constructor: StreamContainer(stream) {#StreamContainer_stream_1}


```
 StreamContainer(stream) 
```

يقوم بإنشاء نسخة جديدة من الفئة [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |

### Constructor: StreamContainer(stream, dispose_stream) {#StreamContainer_stream_dispose_stream_2}


```
 StreamContainer(stream, dispose_stream) 
```

يقوم بإنشاء نسخة جديدة من الفئة [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | دفق البيانات. |
| dispose_stream | bool | إذا تم تعيينه إلى <c>true</c> سيتم التخلص من الدفق عندما يتم التخلص من الحاوية. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_1}


```
 read(buffer, offset, count) 
```

يقرأ تسلسلًا من البايتات من التدفق الحالي ويقدم الموضع داخل التدفق بعدد البايتات المقروءة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| المخزن المؤقت | byte | مصفوفة من البايتات. عندما تعود هذه الطريقة، يحتوي المخزن المؤقت على مصفوفة البايتات المحددة مع القيم بين <paramref name=\"offset\" /> و (<paramref name=\"offset\" /> + <paramref name=\"count\" /> - 1) التي تم استبدالها بالبايتات المقروءة من المصدر الحالي. |
| offset | int | الإزاحة الصفرية للبايت في <paramref name=\"buffer\" /> التي يبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| count | int | الحد الأقصى لعدد البايتات التي سيتم قراءتها من الدفق الحالي. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. قد يكون أقل من عدد البايتات المطلوبة إذا لم تتوفر تلك البايتات حاليًا، أو صفر (0) إذا تم الوصول إلى نهاية الدفق. |


### Method: read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بايت | byte | البايتات التي سيتم ملؤها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | عدد البايتات المقروءة. قد تكون هذه القيمة أقل من عدد البايتات في المخزن المؤقت إذا لم يتوفر ما يكفي من البايتات في الدفق. |


### Method: read_byte() {#read_byte__3}


```
 read_byte() 
```

يقرأ بايتًا من التدفق ويقدم الموضع داخل التدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية التدفق.

**Returns**

| النوع | الوصف |
| :- | :- |
| int | البايت غير الموقّع محوّل إلى Int32، أو -1 إذا كان عند نهاية الدفق. |


### Method: save(destination_stream) {#save_destination_stream_4}


```
 save(destination_stream) 
```

يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) وقيمة [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_5}


```
 save(destination_stream, buffer_size) 
```

يحفظ (ينسخ) جميع بيانات التدفق إلى التدفق المحدد. يستخدم قيمة [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |
| buffer_size | int | المخزن المؤقت. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_6}


```
 save(destination_stream, buffer_size, length) 
```

يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) value is used. |
| length | long | The length of the stream data to copy. By default the length is set to [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |

### Method: save(file_path) {#save_file_path_7}


```
 save(file_path) 
```

يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) وقيمة [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_8}


```
 save(file_path, buffer_size) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) value is used. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_9}


```
 save(file_path, buffer_size, length) 
```

يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | The file path to save the stream data to. |
| buffer_size | int | The buffer size. By default [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) value is used. |
| length | long | The length of the stream data to copy. By default the length is set to [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) value. |

### Method: seek(offset, origin) {#seek_offset_origin_10}


```
 seek(offset, origin) 
```

يضبط الموضع داخل الدفق الحالي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| offset | long | A byte offset relative to the <paramref name=\"origin\" /> parameter. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | A value of type SeekOrigin indicating the reference point used to obtain the new position. |

**Returns**

| النوع | الوصف |
| :- | :- |
| long | The new position within the current stream. |


### Method: to_bytes() {#to_bytes__11}


```
 to_bytes() 
```

يحوّل بيانات الدفق إلى مصفوفة من نوع int.

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | The stream data converted to the int array. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_12}


```
 to_bytes(position, bytes_count) 
```

يحوّل بيانات الدفق إلى مصفوفة من نوع int.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| position | long | The position to start reading bytes from. |
| bytes_count | long | The bytes count to read. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | The stream data converted to the int array. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_13}


```
 write(buffer, offset, count) 
```

يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| المخزن المؤقت | byte | An array of bytes. This method copies <paramref name=\"count\" /> bytes from <paramref name=\"buffer\" /> to the current stream. |
| offset | int | The zero-based byte offset in <paramref name=\"buffer\" /> at which to begin copying bytes to the current stream. |
| count | int | The number of bytes to be written to the current stream. |

### Method: write(bytes) {#write_bytes_14}


```
 write(bytes) 
```

يكتب جميع البايتات المحددة إلى الدفق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بايت | byte | The bytes to write. |

### Method: write_byte(value) {#write_byte_value_15}


```
 write_byte(value) 
```

يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | byte | The byte to write to the stream. |

### Method: write_to(stream_container) {#write_to_stream_container_16}


```
 write_to(stream_container) 
```

ينسخ البيانات المحتواة إلى [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) آخر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to copy to. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_17}


```
 write_to(stream_container, length) 
```

ينسخ البيانات المحتواة إلى [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) آخر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to copy to. |
| الطول | long | The bytes count to write. |

