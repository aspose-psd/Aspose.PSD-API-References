---
title: "IPartialRawDataLoader"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "部分データローダーです。"
type: docs
weight: 133
url: /ja/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

部分データローダーです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | ロードされたデータを処理します。 |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | ロードされたデータを処理します。 |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


ロードされたデータを処理します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | データ矩形。 |
| データ | byte[] | 生データ。 |
| start | [Point](../../com.aspose.psd/point) | 開始データポイントです。(left,top) と等しくない場合、完全な矩形ではないことを意味します。 |
| end | [Point](../../com.aspose.psd/point) | 終了データポイントです。(right,bottom) と等しくない場合、完全な矩形ではないことを意味します。 |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


ロードされたデータを処理します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | データ矩形。 |
| データ | byte[] | 生データ。 |
| start | [Point](../../com.aspose.psd/point) | 開始データポイントです。(left,top) と等しくない場合、完全な矩形ではないことを意味します。 |
| end | [Point](../../com.aspose.psd/point) | 終了データポイントです。(right,bottom) と等しくない場合、完全な矩形ではないことを意味します。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

