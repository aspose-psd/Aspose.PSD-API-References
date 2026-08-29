---
title: "IRasterImagePixelLoader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ラスタ画像ピクセルローダー。"
type: docs
weight: 136
url: /ja/java/com.aspose.psd/irasterimagepixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

ラスタ画像ピクセルローダー。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | ピクセルを部分的に（ブロック単位で）ロードします。 |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


ピクセルを部分的に（ブロック単位で）ロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルを読み込む矩形。 |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | 部分ローダーです。 |

