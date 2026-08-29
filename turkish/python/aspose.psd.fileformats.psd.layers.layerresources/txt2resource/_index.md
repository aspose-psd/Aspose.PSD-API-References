---
title: "Txt2Resource Sınıfı"
type: docs
weight: 970
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Yeni bir Txt2Resource sınıfının örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| veri | byte | r/w | Veriyi alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Metin kaydını Resource'a ekler ve metin kaydının kimliğini döndürür. |
| [get_text_data()](#get_text_data__2) | Metin kaydını resource verisinden alır. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Belirtilen akış konteynerini kaydeder. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Yeni bir Txt2Resource sınıfının örneğini başlatır

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Metin kaydını Resource'a ekler ve metin kaydının kimliğini döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | string | Kayıt metni. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sınırlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Resource için metin kaydının Id'sini döndürür |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Metin kaydını resource verisinden alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Metin kaydı dizisi |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Belirtilen akış konteynerini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |
| psd_version | int | PSD sürümü. |

