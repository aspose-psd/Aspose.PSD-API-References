---
title: "ImageCreatorsRegistry-klass"
type: docs
weight: 2210
url: /sv/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Hämtar de registrerade beskrivarna. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar de registrerade bildskapande formaten. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Skapar den först hittade skaparen som är lämplig för den angivna. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Hämtar den först hittade stödda beskrivaren som är lämplig för den angivna. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Registrerar den angivna bildskaparebeskrivaren. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Registrerar skaparen. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Avregistrerar skaparen. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Skapar den först hittade skaparen som är lämplig för den angivna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bildalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Skaparen som stöder den angivna eller null om ingen sådan skapare hittas. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Hämtar den först hittade stödda beskrivaren som är lämplig för den angivna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bildalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Skaparbearbetarbeskrivaren som stöder den angivna eller null om ingen sådan beskrivare hittas. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Registrerar den angivna bildskaparebeskrivaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Bildskaparbearbetarbeskrivaren. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Registrerar skaparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Skaparbearbetarbeskrivaren att registrera. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Avregistrerar skaparen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Skaparbearbetarbeskrivaren. |

