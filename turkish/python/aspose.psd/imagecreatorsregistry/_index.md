---
title: "ImageCreatorsRegistry Sınıfı"
type: docs
weight: 2210
url: /tr/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Kayıtlı tanımlayıcıları alır. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Kayıtlı görüntü oluşturma biçimlerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Belirtilen için uygun olan ilk bulunan oluşturucuyu oluşturur. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Belirtilen için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Belirtilen görüntü oluşturucu tanımlayıcısını kaydeder. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Oluşturucuyu kaydeder. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Oluşturucunun kaydını siler. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Belirtilen için uygun olan ilk bulunan oluşturucuyu oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Belirtileni destekleyen oluşturucu; böyle bir oluşturucu bulunamazsa null. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Belirtilen için uygun olan ilk bulunan desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Belirtileni destekleyen oluşturucu tanımlayıcısı; böyle bir tanımlayıcı bulunamazsa null. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Belirtilen görüntü oluşturucu tanımlayıcısını kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Görüntü oluşturucu tanımlayıcısı. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Oluşturucuyu kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Kaydedilecek oluşturucu tanımlayıcısı. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Oluşturucunun kaydını siler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Oluşturucu tanımlayıcısı. |

