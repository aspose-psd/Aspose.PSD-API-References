---
title: "ImageLoadersRegistry Sınıfı"
type: docs
weight: 2260
url: /tr/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | Kayıtlı tanımlayıcıları alır. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Kayıtlı görüntü yükleme biçimlerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Belirtilen <paramref name="stream" /> için uygun olan ve isteğe bağlı olarak <paramref name="loadOptions" /> için ilk bulunan yükleyiciyi oluşturur. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Belirtilen <paramref name="stream" /> için uygun olan ve isteğe bağlı olarak <paramref name="loadOptions" /> için ilk bulunan desteklenen tanımlayıcıyı alır. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Tür adıyla ilk desteklenen dosya biçimini alır. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Tür adını kullanarak ilk desteklenen tanımlayıcıyı alır. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Belirtilen görüntü yükleyici tanımlayıcısını kaydeder. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Yükleyiciyi kaydeder. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Yükleyicinin kaydını siler. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Belirtilen <paramref name="stream" /> için uygun olan ve isteğe bağlı olarak <paramref name="loadOptions" /> için ilk bulunan yükleyiciyi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Belirtilen <paramref name="stream" /> ve <paramref name="loadOptions" /> öğelerini destekleyen yükleyici ya da böyle bir yükleyici bulunamazsa null. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Belirtilen <paramref name="stream" /> için uygun olan ve isteğe bağlı olarak <paramref name="loadOptions" /> için ilk bulunan desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Belirtilen <paramref name="stream" /> ve <paramref name="loadOptions" /> öğelerini destekleyen yükleyici tanımlayıcı ya da böyle bir tanımlayıcı bulunamazsa null. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Tür adıyla ilk desteklenen dosya biçimini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | Desteklenen tanımlayıcı dosya biçimi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | İlk bulunan yükleyici tanımlayıcı ya da böyle bir tanımlayıcı bulunamazsa null. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Tür adını kullanarak ilk desteklenen tanımlayıcıyı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| descriptor_type_name | string | Tanımlayıcı tür adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | İlk bulunan yükleyici tanımlayıcı ya da böyle bir tanımlayıcı bulunamazsa null. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Belirtilen görüntü yükleyici tanımlayıcısını kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Görüntü yükleyici tanımlayıcısı. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Yükleyiciyi kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Kaydedilecek yükleyici tanımlayıcısı. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Yükleyicinin kaydını siler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Kaydı silinecek yükleyici tanımlayıcısı. |

