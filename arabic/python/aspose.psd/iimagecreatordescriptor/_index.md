---
title: "الفئة IImageCreatorDescriptor"
type: docs
weight: 1770
url: /ar/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على الصيغة المدعومة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | يحدد ما إذا كان منشئ الصورة يمكنه إنشاء صورة جديدة باستخدام <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | ينشئ مثيلًا جديدًا للمنشئ. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

يحدد ما إذا كان منشئ الصورة يمكنه إنشاء صورة جديدة باستخدام <paramref name="imageOptions" />.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الصورة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>True</c> إذا كان منشئ الصورة الذي تم إنشاؤه بواسطة هذا الوصف يمكنه إنشاء بيانات الصورة باستخدام <paramref name="imageOptions" /> المحدد؛ وإلا، <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

ينشئ مثيلًا جديدًا للمنشئ.

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | مثيل جديد للمنشئ. |


