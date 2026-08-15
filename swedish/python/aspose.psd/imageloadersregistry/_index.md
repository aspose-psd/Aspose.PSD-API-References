---
title: "ImageLoadersRegistry-klass"
type: docs
weight: 2260
url: /sv/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | Hämtar de registrerade beskrivarna. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar de registrerade bildladdningsformaten. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Skapar den först hittade laddaren som är lämplig för den angivna <paramref name="stream" /> och eventuellt <paramref name="loadOptions" />. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Hämtar den först hittade stödjade beskrivaren som är lämplig för den angivna <paramref name="stream" /> och eventuellt <paramref name="loadOptions" />. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Hämtar det första stödda filformatet efter dess typnamn. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Hämtar den första stödjade beskrivaren efter dess typnamn. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registrerar den angivna bildladdarens beskrivning. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registrerar laddaren. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Avregistrerar laddaren. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Skapar den först hittade laddaren som är lämplig för den angivna <paramref name="stream" /> och eventuellt <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Laddaren som stöder den angivna <paramref name="stream" /> och <paramref name="loadOptions" /> eller null om ingen sådan laddare hittas. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Hämtar den först hittade stödjade beskrivaren som är lämplig för den angivna <paramref name="stream" /> och eventuellt <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Laddarbeskrivningen som stöder den angivna <paramref name="stream" /> och <paramref name="loadOptions" /> eller null om ingen sådan beskrivning hittas. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Hämtar det första stödda filformatet efter dess typnamn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | Det stödda beskrivningsfilformatet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Den först hittade laddarbeskrivningen eller null om ingen sådan beskrivning hittas. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Hämtar den första stödjade beskrivaren efter dess typnamn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| descriptor_type_name | string | Beskrivartypens namn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Den först hittade laddarbeskrivningen eller null om ingen sådan beskrivning hittas. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registrerar den angivna bildladdarens beskrivning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Bildladdarens beskrivning. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registrerar laddaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Laddarbeskrivningen att registrera. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Avregistrerar laddaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Laddarbeskrivningen att avregistrera. |

