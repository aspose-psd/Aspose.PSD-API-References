---
title: "LayerResourcesRegistry Sınıfı"
type: docs
weight: 1010
url: /tr/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Kayıtlı tanımlayıcıları alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | İlk desteklenen açıcı tanımlayıcıyı alır. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Tür adını kullanarak ilk desteklenen tanımlayıcıyı alır. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Belirtilen <paramref name=\"stream\" /> için uygun bulunan ilk açıcıyı kullanarak [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) yükler. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Açıcıyı kaydeder. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Açıcıyı kayıttan çıkarır. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

İlk desteklenen açıcı tanımlayıcıyı alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| psd_version | int | PSD sürümü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Katman kaynağı yükleyici tanımlayıcısı veya böyle bir akış için desteklenen yükleyici tanımlayıcısı yoksa null. |


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Bulunan ilk açıcı tanımlayıcısı veya böyle bir tanımlayıcı bulunamazsa null. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Belirtilen <paramref name=\"stream\" /> için uygun bulunan ilk açıcıyı kullanarak [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |
| psd_version | int | PSD sürümü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Yüklenen [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) veya açıcı bulunamazsa null. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Açıcıyı kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Kaydedilecek açıcı tanımlayıcısı. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Açıcıyı kayıttan çıkarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Kayıttan çıkarılacak açıcı tanımlayıcısı. |

