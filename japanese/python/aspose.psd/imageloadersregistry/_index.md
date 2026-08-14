---
title: "ImageLoadersRegistry クラス"
type: docs
weight: 2260
url: /ja/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | 登録された記述子を取得します。 |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 登録されている画像読み込み形式を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | 指定された <paramref name="stream" /> に適合し、オプションで <paramref name="loadOptions" /> に適合する最初に見つかったローダーを作成します。 |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | 指定された <paramref name="stream" /> に適合し、オプションで <paramref name="loadOptions" /> に適合する最初に見つかったサポートされている記述子を取得します。 |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | 型名で最初にサポートされているファイル形式を取得します。 |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | タイプ名で最初にサポートされている記述子を取得します。 |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | 指定された画像ローダー記述子を登録します。 |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | ローダーを登録します。 |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | ローダーの登録を解除します。 |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

指定された <paramref name="stream" /> に適合し、オプションで <paramref name="loadOptions" /> に適合する最初に見つかったローダーを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ストリーム。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | ロードオプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | 指定された <paramref name="stream" /> と <paramref name="loadOptions" /> をサポートするローダー、または該当するローダーが見つからない場合は null。 |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

指定された <paramref name="stream" /> に適合し、オプションで <paramref name="loadOptions" /> に適合する最初に見つかったサポートされている記述子を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ストリーム。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | ロードオプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 指定された <paramref name="stream" /> と <paramref name="loadOptions" /> をサポートするローダー記述子、または該当する記述子が見つからない場合は null。 |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

型名で最初にサポートされているファイル形式を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | サポートされている記述子のファイル形式。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 最初に見つかったローダー記述子、または該当する記述子が見つからない場合は null。 |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

タイプ名で最初にサポートされている記述子を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| descriptor_type_name | string | 記述子タイプ名。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 最初に見つかったローダー記述子、または該当する記述子が見つからない場合は null。 |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

指定された画像ローダー記述子を登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 画像ローダー記述子。 |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

ローダーを登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 登録するローダー記述子。 |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

ローダーの登録を解除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 登録解除するローダー記述子。 |

