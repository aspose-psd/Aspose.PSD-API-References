---
title: "IopaResource Sınıfı"
type: docs
weight: 440
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Yeni bir [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) sınıfının örneğini başlatır. |
| [IopaResource(data)](#IopaResource_data_2) | Yeni bir [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| dolgu_opaklığı | byte | r/w | Dolgu opaklığını alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Yeni bir [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) sınıfının örneğini başlatır.

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Yeni bir [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Ham bayt verisi. |

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

