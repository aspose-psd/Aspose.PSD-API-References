---
title: "FxrpResource Sınıfı"
type: docs
weight: 320
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | Yeni bir [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) sınıfı örneği başlatır. |
| [FxrpResource(data)](#FxrpResource_data_2) | Yeni bir [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) sınıfı örneği başlatır.<br/>            Özel veya bilinmeyen değer ile |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | Yeni bir [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| x | double | r/w | Referans noktasının x değerini alır veya ayarlar. |
| y | double | r/w | Referans noktasının y değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Belirtilen akış konteynerine kaydeder. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

Yeni bir [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) sınıfı örneği başlatır.

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

Yeni bir [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) sınıfı örneği başlatır.<br/>            Özel veya bilinmeyen değer ile

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Kaynak verisi. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

Yeni bir [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | double | Referans noktasının x koordinatı |
| y | double | Referans noktasının y koordinatı |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| psd_version | int | PSD sürümü. |

