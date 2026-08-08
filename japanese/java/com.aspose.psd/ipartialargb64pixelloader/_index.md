---
title: "IPartialArgb64PixelLoader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "64ビットARGBピクセルローダーです。"
type: docs
weight: 131
url: /ja/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

64ビットARGBピクセルローダーです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | ロードされたピクセルを処理します。 |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


ロードされたピクセルを処理します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルの矩形。 |
| ピクセル | long[] | 64ビット ARGB ピクセル。 |
| start | [Point](../../com.aspose.psd/point) | 開始ピクセルのポイントです。(left,top)と等しくない場合、矩形が完全でないことを意味します。 |
| end | [Point](../../com.aspose.psd/point) | 終了ピクセルのポイントです。(right,bottom)と等しくない場合、矩形が完全でないことを意味します。 |

