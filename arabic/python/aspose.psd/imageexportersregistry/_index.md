---
title: "الفئة ImageExportersRegistry"
type: docs
weight: 2230
url: /ar/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | يحصل على أوصاف المُصدِّر المسجَّل. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على صيغ التصدير المسجلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | ينشئ أول مُصدِّر تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | يحصل على أول وصف مدعوم تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | يسجل وصف مُصدِّر الصورة المحدد. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | يسجل المُصدِّر. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | يلغي تسجيل المُصدِّر. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

ينشئ أول مُصدِّر تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة المراد تصديرها. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ المستخدمة للتصدير. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | المُصدِّر الذي يدعم الصورة المحددة وخيارات الحفظ أو null إذا لم يُعثر على مُصدِّر مماثل. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

يحصل على أول وصف مدعوم تم العثور عليه مناسب لخيارات الحفظ المحددة والصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | الصورة المراد تصديرها. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | وصف المُصدِّر الذي يدعم الصورة المحددة وخيارات الحفظ أو null إذا لم يُعثر على وصف مماثل. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

يسجل وصف مُصدِّر الصورة المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | وصف مُصدِّر الصورة. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

يسجل المُصدِّر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | وصف المُصدِّر للتسجيل. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

يلغي تسجيل المُصدِّر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | وصف المُصدِّر لإلغاء التسجيل. |

