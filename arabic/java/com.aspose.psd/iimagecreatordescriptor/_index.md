---
title: "IImageCreatorDescriptor"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "وصف منشئ الصورة الذي يحدد خصائص المنشئ."
type: docs
weight: 119
url: /ar/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

وصف image creator descriptor الذي يحدد creator properties. يُستخدم وصف creator descriptor لتجاوز الحاجة إلى احتواء كل مثال image creator في الذاكرة ومشكلات تعدد الخيوط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | يحدد ما إذا كان image creator يمكنه إنشاء صورة جديدة باستخدام imageOptions . |
| [createInstance()](#createInstance--) | ينشئ مثال creator جديد. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


يحدد ما إذا كان image creator يمكنه إنشاء صورة جديدة باستخدام imageOptions .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الصورة. |

**Returns:**
منطقي - true إذا كان image creator الذي أنشأه هذا الوصف يمكنه إنشاء بيانات صورة باستخدام imageOptions المحدد؛ وإلا، false.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


ينشئ مثال creator جديد.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
