---
title: "IImageCreator"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "منشئ الصورة."
type: docs
weight: 118
url: /ar/java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

منشئ الصورة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | ينشئ نسخة جديدة من الصورة باستخدام imageOptions. |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


ينشئ نسخة جديدة من الصورة باستخدام imageOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق لإنشاء بيانات الصورة فيها. |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات الصورة. |
| العرض | int | عرض الصورة الجديدة |
| الارتفاع | int | ارتفاع الصورة الجديدة |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
