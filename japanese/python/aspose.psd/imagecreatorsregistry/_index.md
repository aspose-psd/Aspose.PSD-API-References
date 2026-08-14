---
title: "ImageCreatorsRegistry クラス"
type: docs
weight: 2210
url: /ja/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | 登録された記述子を取得します。 |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 登録されている画像作成フォーマットを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | 指定された条件に適した最初に見つかったクリエーターを作成します。 |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | 指定された条件に適した最初に見つかったサポートされている記述子を取得します。 |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | 指定された画像クリエーター記述子を登録します。 |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | クリエーターを登録します。 |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | クリエーターの登録を解除します。 |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

指定された条件に適した最初に見つかったクリエーターを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 画像オプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | 指定されたものをサポートするクリエーター、または見つからない場合は null です。 |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

指定された条件に適した最初に見つかったサポートされている記述子を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 画像オプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 指定されたものをサポートするクリエーター記述子、または見つからない場合は null です。 |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

指定された画像クリエーター記述子を登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 画像クリエーター記述子です。 |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

クリエーターを登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 登録するクリエイターディスクリプタ。 |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

クリエーターの登録を解除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | クリエイターディスクリプタ。 |

