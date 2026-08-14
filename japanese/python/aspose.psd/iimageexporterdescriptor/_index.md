---
title: "IImageExporterDescriptor クラス"
type: docs
weight: 1800
url: /ja/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | サポートされている形式を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | 画像エクスポーターが、保存オプションで指定された画像形式に指定された画像をエクスポートできるかどうかを判断します。 |
| [create_instance()](#create_instance__2) | 新しいエクスポーターインスタンスを作成します。 |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

画像エクスポーターが、保存オプションで指定された画像形式に指定された画像をエクスポートできるかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | エクスポートする画像。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプションのベースです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <c>True</c> は、この記述子によって作成されたエクスポーターが指定された画像を指定されたファイル形式にエクスポートできる場合です。そうでない場合は、<c>false</c> です。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

新しいエクスポーターインスタンスを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | 新しいエクスポーターインスタンスです。 |


