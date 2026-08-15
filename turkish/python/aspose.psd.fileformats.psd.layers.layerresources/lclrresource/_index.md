---
title: "LclrResource Sınıfı"
type: docs
weight: 470
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) sınıfının yeni bir örneğini başlatır. |
| [LclrResource(color)](#LclrResource_color_2) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) sınıfının yeni bir örneğini başlatır. |
| [LclrResource(data)](#LclrResource_data_3) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | Katmanın rengini alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) sınıfının yeni bir örneğini başlatır.

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | Renk. |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) sınıfının yeni bir örneğini başlatır.

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

