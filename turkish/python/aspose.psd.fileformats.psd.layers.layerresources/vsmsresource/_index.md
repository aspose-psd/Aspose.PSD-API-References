---
title: "VsmsResource Sınıfı"
type: docs
weight: 1130
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---

**Summary:** Class VsmsResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VsmsResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [VsmsResource()](#VsmsResource__1) | Yeni bir [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) sınıfı örneği başlatır. |
| [VsmsResource(data)](#VsmsResource_data_2) | Yeni bir [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| is_disabled | bool | r/w | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| is_inverted | bool | r/w | Bu örneğin ters çevrilip çevrilmediğini gösteren bir değeri alır veya ayarlar. |
| is_not_linked | bool | r/w | Bu örneğin bağlanmamış olduğunu gösteren bir değeri alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Yol kayıtlarını alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| version | int | r/w | Sürümü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: VsmsResource() {#VsmsResource__1}


```
 VsmsResource() 
```

Yeni bir [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) sınıfı örneği başlatır.

### Constructor: VsmsResource(data) {#VsmsResource_data_2}


```
 VsmsResource(data) 
```

Yeni bir [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Kaynak verisi. |

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

