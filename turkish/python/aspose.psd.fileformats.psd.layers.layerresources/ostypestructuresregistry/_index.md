---
title: "OSTypeStructuresRegistry Sınıfı"
type: docs
weight: 720
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Kayıtlı tanımlayıcıları alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | İlk desteklenen açıcı tanımlayıcıyı alır. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Tür adını kullanarak ilk desteklenen tanımlayıcıyı alır. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Belirtilen <paramref name=\"stream\" /> için uygun ilk bulunan açıcıyı kullanarak [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) yükler. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Açıcıyı kaydeder. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Açıcıyı kayıttan çıkarır. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

İlk desteklenen açıcı tanımlayıcıyı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Katman kaynağı yükleyici tanımlayıcısı veya böyle bir akış için desteklenen yükleyici tanımlayıcısı yoksa null. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


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
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Bulunan ilk açıcı tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Belirtilen <paramref name=\"stream\" /> için uygun ilk bulunan açıcıyı kullanarak [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Yüklenen [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) veya açıcı bulunamazsa null. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Açıcıyı kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Kaydedilecek açıcı tanımlayıcısı. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Açıcıyı kayıttan çıkarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Kayıttan çıkarılacak açıcı tanımlayıcısı. |

