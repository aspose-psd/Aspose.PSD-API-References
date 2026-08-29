---
title: "ImageExportersRegistry Sınıfı"
type: docs
weight: 2230
url: /tr/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Kayıtlı dışa aktarıcı tanımlayıcılarını alır. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Kayıtlı dışa aktarma formatlarını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk dışa aktarıcıyı oluşturur. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk desteklenen tanımlayıcıyı alır. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | İhracatçıyı kaydeder. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | İhracatçının kaydını siler. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk dışa aktarıcıyı oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Dışa aktarılacak görüntü. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Dışa aktarma için kullanılacak kaydetme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Belirtilen görüntü ve kaydetme seçeneklerini destekleyen ihracatçı veya böyle bir ihracatçı bulunamazsa null. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Belirtilen kaydetme seçenekleri ve görüntü için uygun bulunan ilk desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Dışa aktarılacak görüntü. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Belirtilen görüntü ve kaydetme seçeneklerini destekleyen ihracatçı tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Belirtilen görüntü dışa aktarıcı tanımlayıcısını kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Görüntü ihracatçı tanımlayıcısı. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

İhracatçıyı kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Kaydedilecek ihracatçı tanımlayıcısı. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

İhracatçının kaydını siler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Kaydı silinecek ihracatçı tanımlayıcısı. |

