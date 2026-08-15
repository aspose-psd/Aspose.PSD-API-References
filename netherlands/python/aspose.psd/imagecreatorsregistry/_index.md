---
title: "ImageCreatorsRegistry klasse"
type: docs
weight: 2210
url: /nl/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Haalt de geregistreerde descriptors op. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt de geregistreerde afbeeldingscreatieformaten op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Maakt de eerst gevonden maker aan die geschikt is voor de opgegeven. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registreert de opgegeven afbeeldingsmakerdescriptor. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registreert de maker. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Deregistreert de maker. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Maakt de eerst gevonden maker aan die geschikt is voor de opgegeven.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De afbeeldingopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | De maker die de opgegeven ondersteunt of null als zo'n maker niet wordt gevonden. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De afbeeldingopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | De makerdescriptor die de opgegeven ondersteunt of null als zo'n descriptor niet wordt gevonden. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registreert de opgegeven afbeeldingsmakerdescriptor.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | De afbeeldingsmakerdescriptor. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registreert de maker.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | De makerdescriptor om te registreren. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Deregistreert de maker.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | De makerdescriptor. |

