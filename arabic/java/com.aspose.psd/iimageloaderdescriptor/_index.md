---
title: "IImageLoaderDescriptor"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "وصف محمل الصورة الذي يحدد خصائص المحمل."
type: docs
weight: 124
url: /ar/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

وصف محمل الصورة الذي يحدد خصائص المحمل. يُستخدم وصف المحمل لتجاوز الحاجة إلى احتواء كل مثال من محمل الصورة في الذاكرة ومشكلات تعدد الخيوط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام loadOptions اختياريًا. |
| [createInstance()](#createInstance--) | ينشئ مثالًا جديدًا للمحمل. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


يحدد ما إذا كان محمل الصورة يمكنه قراءة صورة جديدة من الدفق المحدد واستخدام loadOptions اختياريًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | تفاصيل تنسيق الملف المحددة بواسطة loadOptions. قد تكون loadOptions فارغة. |

**Returns:**
منطقي - true إذا كان محمل الصورة الذي أنشئه هذا الوصف يمكنه قراءة الصورة من الدفق؛ وإلا false.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


ينشئ مثالًا جديدًا للمحمل.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
