---
title: "Clase ImageCreatorsRegistry"
type: docs
weight: 2210
url: /es/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Obtiene los descriptores registrados. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtiene los formatos de creación de imágenes registrados. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Crea el primer creador encontrado que sea adecuado para lo especificado. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Obtiene el primer descriptor compatible encontrado adecuado para el especificado. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registra el descriptor de creador de imagen especificado. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registra el creador. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Anula el registro del creador. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Crea el primer creador encontrado que sea adecuado para lo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | El creador que soporta lo especificado o null si no se encuentra tal creador. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Obtiene el primer descriptor compatible encontrado adecuado para el especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | El descriptor del creador que soporta lo especificado o null si no se encuentra tal descriptor. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registra el descriptor de creador de imagen especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | El descriptor del creador de imagen. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registra el creador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | El descriptor del creador a registrar. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Anula el registro del creador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | El descriptor del creador. |

