---
title: "فئة IImageLoaderDescriptor"
type: docs
weight: 1820
url: /ar/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على الصيغة المدعومة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام <paramref name="loadOptions" /> اختياريًا. |
| [create_instance()](#create_instance__2) | ينشئ مثيلًا جديدًا للمحمّل. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام <paramref name="loadOptions" /> اختياريًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | تفاصيل تنسيق الملف المحددة بواسطة <paramref name="loadOptions" />. قد يكون <paramref name="loadOptions" /> فارغًا. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان محمل الصورة الذي أنشئه هذا الوصف يمكنه قراءة الصورة من الدفق؛ وإلا فإن <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

ينشئ مثيلًا جديدًا للمحمّل.

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | مثيل جديد للمحمّل. |


