---
title: "Classe ImageCreatorsRegistry"
type: docs
weight: 2210
url: /it/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Ottiene i descrittori registrati. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Restituisce i formati di creazione immagine registrati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Crea il primo creatore trovato adatto a quello specificato. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Ottiene il primo descrittore supportato trovato adatto a quello specificato. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registra il descrittore del creatore di immagini specificato. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registra il creatore. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Annulla la registrazione del creatore. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Crea il primo creatore trovato adatto a quello specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Le opzioni dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Il creatore che supporta quello specificato o null se non viene trovato alcun creatore corrispondente. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Ottiene il primo descrittore supportato trovato adatto a quello specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Le opzioni dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Il descrittore del creatore che supporta quello specificato o null se non viene trovato alcun descrittore corrispondente. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registra il descrittore del creatore di immagini specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Il descrittore del creatore di immagini. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registra il creatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Il descrittore del creatore da registrare. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Annulla la registrazione del creatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Il descrittore del creatore. |

