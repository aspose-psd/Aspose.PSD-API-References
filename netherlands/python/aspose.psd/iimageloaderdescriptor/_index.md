---
title: "IImageLoaderDescriptor Klasse"
type: docs
weight: 1820
url: /nl/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt het ondersteunde formaat op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Bepaalt of de afbeeldingslader een nieuwe afbeelding kan lezen van de opgegeven stream en eventueel met behulp van de <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Maakt een nieuw lader‑object aan. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Bepaalt of de afbeeldingslader een nieuwe afbeelding kan lezen van de opgegeven stream en eventueel met behulp van de <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De bestandsformaatdetails gespecificeerd door <paramref name="loadOptions" />. De <paramref name="loadOptions" /> kan null zijn. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als de door deze descriptor gemaakte afbeeldingslader een afbeelding kan lezen van de stream; anders <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Maakt een nieuw lader‑object aan.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Een nieuw lader‑object. |


