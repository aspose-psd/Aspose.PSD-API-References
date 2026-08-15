---
title: "CustResource Sınıfı"
type: docs
weight: 230
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CustResource()](#CustResource__1) | Yeni bir [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) sınıfı örneği başlatır. |
| [CustResource(data)](#CustResource_data_2) | Yeni bir [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| key | int | r | Katman kaynağı anahtarını alır. |
| layer_created_date_time | datetime | r/w | Katmanın oluşturulma tarihini alır veya ayarlar. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Yeni bir [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) sınıfı örneği başlatır.

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Yeni bir [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Kaynağın verisi. |

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

