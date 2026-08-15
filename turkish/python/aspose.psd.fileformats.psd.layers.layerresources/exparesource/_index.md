---
title: "ExpaResource Sınıfı"
type: docs
weight: 280
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Yeni bir [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) sınıfı örneği başlatır. |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Yeni bir [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) sınıfı örneği başlatır. |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Yeni bir [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| pozlama | float | r/w | Pozlamayı alır veya ayarlar. |
| gama_düzeltme | float | r/w | Gamayı alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| offset | float | r/w | Ofseti alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| version | short | r | Sürümü alır. Varsayılan 1'dir. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Yeni bir [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) sınıfı örneği başlatır.

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Yeni bir [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bayt | byte | Baytlar. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Yeni bir [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pozlama | float | Pozlama. |
| offset | float | Ofset. |
| gamma | float | Gamma. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

