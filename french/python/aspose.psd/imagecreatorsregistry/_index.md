---
title: "ImageCreatorsRegistry Classe"
type: docs
weight: 2210
url: /fr/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Obtient les descripteurs enregistrés. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtient les formats de création d'images enregistrés. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Crée le premier créateur trouvé adapté à celui spécifié. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Obtient le premier descripteur pris en charge trouvé adapté au spécifié. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Enregistre le descripteur de créateur d'image spécifié. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Enregistre le créateur. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Désenregistre le créateur. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Crée le premier créateur trouvé adapté à celui spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'image. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Le créateur qui prend en charge le spécifié ou null si aucun créateur de ce type n'est trouvé. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Obtient le premier descripteur pris en charge trouvé adapté au spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'image. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Le descripteur de créateur qui prend en charge le spécifié ou null si aucun descripteur de ce type n'est trouvé. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Enregistre le descripteur de créateur d'image spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Le descripteur de créateur d'image. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Enregistre le créateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Le descripteur de créateur à enregistrer. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Désenregistre le créateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Le descripteur de créateur. |

