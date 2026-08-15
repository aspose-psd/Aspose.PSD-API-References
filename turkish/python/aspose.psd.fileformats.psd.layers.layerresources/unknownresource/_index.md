---
title: "UnknownResource Sınıfı"
type: docs
weight: 1050
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/
---

**Summary:** The unknown resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.UnknownResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [UnknownResource(signature, key)](#UnknownResource_signature_key_1) | Yeni bir [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| veri | byte | r/w | Veriyi alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | Katman kaynağı imzasını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Belirtilen akış konteynerini kaydeder. |


### Constructor: UnknownResource(signature, key) {#UnknownResource_signature_key_1}


```
 UnknownResource(signature, key) 
```

Yeni bir [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signature | int | İmza. |
| key | int | Kaynak anahtarı. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Belirtilen akış konteynerini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| psd_version | int | PSD sürümü. |

