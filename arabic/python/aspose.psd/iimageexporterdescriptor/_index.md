---
title: "IImageExporterDescriptor الفئة"
type: docs
weight: 1800
url: /ar/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على الصيغة المدعومة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | يحدد ما إذا كان مُصدِّر الصورة يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ. |
| [create_instance()](#create_instance__2) | ينشئ نسخة جديدة من المُصدِّر. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

يحدد ما إذا كان مُصدِّر الصورة يمكنه تصدير الصورة المحددة إلى تنسيق الصورة المحدد وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة المراد تصديرها. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | قاعدة الخيارات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>True</c> إذا كان المُصدِّر الذي أنشأه هذا الوصف يمكنه تصدير الصورة المحددة إلى تنسيق الملف المحدد؛ وإلا، <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

ينشئ نسخة جديدة من المُصدِّر.

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | مثيل جديد للمُصدِّر. |


