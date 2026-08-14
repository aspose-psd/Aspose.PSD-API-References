---
title: "IImageCreatorDescriptor クラス"
type: docs
weight: 1770
url: /ja/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | サポートされている形式を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | 画像クリエイターが <paramref name="imageOptions" /> を使用して新しい画像を作成できるかどうかを決定します。 |
| [create_instance()](#create_instance__2) | 新しいクリエイターインスタンスを作成します。 |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

画像クリエイターが <paramref name="imageOptions" /> を使用して新しい画像を作成できるかどうかを決定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 画像オプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <c>True</c> は、この記述子によって作成された画像クリエイターが指定された <paramref name="imageOptions" /> を使用して画像データを作成できる場合です。そうでない場合は、<c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

新しいクリエイターインスタンスを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | 新しいクリエイターインスタンス。 |


