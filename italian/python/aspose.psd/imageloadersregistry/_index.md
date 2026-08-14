---
title: "Classe ImageLoadersRegistry"
type: docs
weight: 2260
url: /it/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | Ottiene i descrittori registrati. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Restituisce i formati di caricamento immagine registrati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Crea il primo loader trovato adatto allo <paramref name="stream" /> specificato e, opzionalmente, al <paramref name="loadOptions" />. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Restituisce il primo descrittore supportato trovato adatto allo <paramref name="stream" /> specificato e, opzionalmente, al <paramref name="loadOptions" />. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Restituisce il primo formato file supportato per nome del tipo. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Ottiene il primo descrittore supportato per nome del tipo. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Registra il descrittore del loader immagine specificato. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Registra il loader. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Deregistra il loader. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Crea il primo loader trovato adatto allo <paramref name="stream" /> specificato e, opzionalmente, al <paramref name="loadOptions" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Il flusso. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Il loader che supporta lo <paramref name="stream" /> e il <paramref name="loadOptions" /> specificati, oppure null se non viene trovato alcun loader. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Restituisce il primo descrittore supportato trovato adatto allo <paramref name="stream" /> specificato e, opzionalmente, al <paramref name="loadOptions" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Il flusso. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Il descrittore del loader che supporta lo <paramref name="stream" /> e il <paramref name="loadOptions" /> specificati, oppure null se non viene trovato alcun descrittore. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Restituisce il primo formato file supportato per nome del tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | Il formato file del descrittore supportato. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Il primo descrittore del loader trovato, oppure null se non viene trovato alcun descrittore. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Ottiene il primo descrittore supportato per nome del tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| descriptor_type_name | string | Il nome del tipo di descrittore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Il primo descrittore del loader trovato, oppure null se non viene trovato alcun descrittore. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Registra il descrittore del loader immagine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Il descrittore del loader immagine. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Registra il loader.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Il descrittore del loader da registrare. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Deregistra il loader.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Il descrittore del loader da deregistrare. |

