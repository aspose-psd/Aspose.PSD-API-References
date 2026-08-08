---
title: "IPartialArgb32PixelLoader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "部分的に読み込まれた32ビットARGBピクセルに準拠します。"
type: docs
weight: 130
url: /ja/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

部分的に読み込まれた32ビットARGBピクセルに準拠します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | ロードされたピクセルを処理します。 |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


ロードされたピクセルを処理します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルの矩形。 |
| ピクセル | int[] | ARGB形式のピクセル |
| start | [Point](../../com.aspose.psd/point) | 開始ピクセルのポイントです。(left,top)と等しくない場合、矩形が完全でないことを意味します。 |
| end | [Point](../../com.aspose.psd/point) | 終了ピクセルのポイントです。(right,bottom)と等しくない場合、矩形が完全でないことを意味します。 |

