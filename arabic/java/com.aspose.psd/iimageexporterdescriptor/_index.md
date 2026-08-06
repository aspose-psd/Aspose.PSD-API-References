---
title: "IImageExporterDescriptor"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل وصف مُصدّر الصورة."
type: docs
weight: 122
url: /ar/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

يمثل موصِّف مُصدِّر الصورة. يُستخدم موصِّف المُصدِّر لتجاوز الحاجة إلى احتواء كل نسخة من المُصدِّر في الذاكرة ومشكلات تعدد الخيوط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | يحدد ما إذا كان مُصدِّر الصورة يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ. |
| [createInstance()](#createInstance--) | ينشئ نسخة جديدة من المُصدِّر. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


يحدد ما إذا كان مُصدِّر الصورة يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | الصورة المراد تصديرها. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | قاعدة الخيارات. |

**Returns:**
منطقي -  true  إذا كان المُصدّر الذي أنشأه هذا الوصف يمكنه تصدير الصورة المحددة إلى تنسيق الملف المحدد؛ وإلا،  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


ينشئ نسخة جديدة من المُصدِّر.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
