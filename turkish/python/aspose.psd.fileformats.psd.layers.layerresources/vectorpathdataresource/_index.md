---
title: "VectorPathDataResource Sınıfı"
type: docs
weight: 1080
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---

**Summary:** Class VectorPathDataResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VectorPathDataResource

**Inheritance:** IVectorPathData, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
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

