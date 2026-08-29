---
title: "InfxResource Sınıfı"
type: docs
weight: 420
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) sınıfının yeni bir örneğini başlatır. |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) sınıfının yeni bir örneğini başlatır. |
| [InfxResource(data)](#InfxResource_data_3) | [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) sınıfının yeni bir örneğini başlatır.<br/>            Özel veya bilinmeyen değerle |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| blend_interior_elements | bool | r/w | [blend interior elements] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Belirtilen akış konteynerini kaydeder. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) sınıfının yeni bir örneğini başlatır.

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| blend_interior_elements | bool | eğer <c>true</c> olarak ayarlanırsa [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

[InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) sınıfının yeni bir örneğini başlatır.<br/>            Özel veya bilinmeyen değerle

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Kaynak verisi. |

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

