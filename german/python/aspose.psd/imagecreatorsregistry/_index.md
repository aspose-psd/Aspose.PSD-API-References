---
title: "ImageCreatorsRegistry Klasse"
type: docs
weight: 2210
url: /de/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Liest die registrierten Deskriptoren. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ermittelt die registrierten Bild-Erstellungsformate. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Erzeugt den zuerst gefundenen Ersteller, der für das Angegebene geeignet ist. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Ermittelt den zuerst gefundenen unterstützten Deskriptor, der für das Angegebene geeignet ist. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registriert den angegebenen Bild-Ersteller-Deskriptor. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registriert den Ersteller. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Deregistriert den Ersteller. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Erzeugt den zuerst gefundenen Ersteller, der für das Angegebene geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Bildoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Der Ersteller, der das Angegebene unterstützt, oder null, wenn kein solcher Ersteller gefunden wird. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Ermittelt den zuerst gefundenen unterstützten Deskriptor, der für das Angegebene geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Bildoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Der Ersteller-Deskriptor, der das Angegebene unterstützt, oder null, wenn kein solcher Deskriptor gefunden wird. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registriert den angegebenen Bild-Ersteller-Deskriptor.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Der Bild-Ersteller-Deskriptor. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registriert den Ersteller.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Der zu registrierende Ersteller-Deskriptor. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Deregistriert den Ersteller.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Der Ersteller-Deskriptor. |

