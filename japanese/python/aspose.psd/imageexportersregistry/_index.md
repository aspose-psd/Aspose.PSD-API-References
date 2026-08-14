---
title: "ImageExportersRegistry クラス"
type: docs
weight: 2230
url: /ja/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | 登録されているエクスポーター記述子を取得します。 |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 登録されているエクスポート形式を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | 指定された保存オプションと画像に適した最初に見つかったエクスポーターを作成します。 |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | 指定された保存オプションと画像に適した最初に見つかったサポートされている記述子を取得します。 |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | 指定された画像エクスポーター記述子を登録します。 |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | エクスポーターを登録します。 |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | エクスポーターの登録を解除します。 |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

指定された保存オプションと画像に適した最初に見つかったエクスポーターを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | エクスポートする画像。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | エクスポートに使用する保存オプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | 指定された画像と保存オプションをサポートするエクスポーター、またはそのようなエクスポーターが見つからない場合は null。 |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

指定された保存オプションと画像に適した最初に見つかったサポートされている記述子を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | エクスポートする画像。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 指定された画像と保存オプションをサポートするエクスポーター記述子、またはそのような記述子が見つからない場合は null。 |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

指定された画像エクスポーター記述子を登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 画像エクスポーター記述子。 |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

エクスポーターを登録します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 登録するエクスポーター記述子。 |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

エクスポーターの登録を解除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 登録解除するエクスポーター記述子。 |

