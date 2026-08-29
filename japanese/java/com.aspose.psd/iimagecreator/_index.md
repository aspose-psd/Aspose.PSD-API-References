---
title: "IImageCreator"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "画像クリエイターです。"
type: docs
weight: 118
url: /ja/java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

画像クリエイターです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | imageOptions を使用して新しい画像インスタンスを作成します。 |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


imageOptions を使用して新しい画像インスタンスを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 画像データを作成するためのストリームコンテナです。 |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 画像オプション。 |
| 幅 | int | 新しい画像の幅 |
| 高さ | int | 新しい画像の高さ |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
