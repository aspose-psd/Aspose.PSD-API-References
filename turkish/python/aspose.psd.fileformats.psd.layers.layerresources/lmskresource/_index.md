---
title: "LmskResource Sınıfı"
type: docs
weight: 560
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Summary:** The LMsk resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LmskResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LmskResource()](#LmskResource__1) | Yeni bir [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| color_component1 | ushort | r/w | Renk bileşeni 1'i alır. |
| color_component2 | ushort | r/w | Renk bileşeni 2'yi alır. |
| color_component3 | ushort | r/w | Renk bileşeni 3'ü alır. |
| color_component4 | ushort | r/w | Renk bileşeni 4'ü alır. |
| color_space | [ColorSpace](/psd/python-net/aspose.psd.fileformats.psd.resources.enums/colorspace/) | r/w | Renk uzayını alır. |
| flag | byte | r | Bayrağı alır. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| opaklık | short | r/w | Saydamlığı alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Kaynağı belirtilen akış konteynerine kaydeder. |


### Constructor: LmskResource() {#LmskResource__1}


```
 LmskResource() 
```

Yeni bir [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) sınıfının örneğini başlatır.

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

