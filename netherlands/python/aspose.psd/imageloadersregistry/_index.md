---
title: "ImageLoadersRegistry Klasse"
type: docs
weight: 2260
url: /nl/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | Haalt de geregistreerde descriptors op. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt de geregistreerde afbeeldingslaadformaten op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Maakt de eerst gevonden loader die geschikt is voor de opgegeven <paramref name="stream" /> en eventueel de <paramref name="loadOptions" /> aan. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven <paramref name="stream" /> en eventueel de <paramref name="loadOptions" />. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Haalt het eerst ondersteunde bestandsformaat op via de type‑naam. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Haalt de eerste ondersteunde descriptor op basis van de type-naam. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registreert de opgegeven afbeeldingsloader‑descriptor. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registreert de loader. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Deregistreert de loader. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Maakt de eerst gevonden loader die geschikt is voor de opgegeven <paramref name="stream" /> en eventueel de <paramref name="loadOptions" /> aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | De loader die de opgegeven <paramref name="stream" /> en <paramref name="loadOptions" /> ondersteunt, of null als zo'n loader niet wordt gevonden. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven <paramref name="stream" /> en eventueel de <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | De loader‑descriptor die de opgegeven <paramref name="stream" /> en <paramref name="loadOptions" /> ondersteunt, of null als zo'n descriptor niet wordt gevonden. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Haalt het eerst ondersteunde bestandsformaat op via de type‑naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | Het ondersteunde descriptor‑bestandsformaat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | De eerst gevonden loader‑descriptor of null als zo'n descriptor niet wordt gevonden. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Haalt de eerste ondersteunde descriptor op basis van de type-naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| descriptor_type_name | string | De descriptor type naam. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | De eerst gevonden loader‑descriptor of null als zo'n descriptor niet wordt gevonden. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registreert de opgegeven afbeeldingsloader‑descriptor.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | De afbeeldingsloader‑descriptor. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registreert de loader.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | De loader‑descriptor om te registreren. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Deregistreert de loader.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | De loader‑descriptor om te deregistreren. |

