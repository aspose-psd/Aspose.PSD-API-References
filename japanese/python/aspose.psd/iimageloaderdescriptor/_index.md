---
title: "IImageLoaderDescriptor クラス"
type: docs
weight: 1820
url: /ja/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | サポートされている形式を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | 指定されたストリームから新しい画像を読み取れるかどうかを判定し、オプションで <paramref name=\"loadOptions\" /> を使用します。 |
| [create_instance()](#create_instance__2) | 新しいローダー インスタンスを作成します。 |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

指定されたストリームから新しい画像を読み取れるかどうかを判定し、オプションで <paramref name=\"loadOptions\" /> を使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | <paramref name=\"loadOptions\" /> で指定されたファイル形式の詳細です。<paramref name=\"loadOptions\" /> は null の可能性があります。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | この記述子によって作成された画像ローダーがストリームから画像を読み取れる場合は <c>true</c>、それ以外の場合は <c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

新しいローダー インスタンスを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | 新しいローダー インスタンス。 |


