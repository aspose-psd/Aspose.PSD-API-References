---
title: "RasterImage.GetPixel"
second_title: "Aspose.PSD for .NET API Reference"
description: "RasterImage メソッド。画像のピクセルを取得します。パフォーマンス警告：このメソッドを使用してすべての画像ピクセルを反復処理しないでください。パフォーマンスに重大な影響を与える可能性があります。より効率的なピクセル操作のためには、LoadArgb32Pixels メソッドを使用してピクセル配列全体を同時に取得してください。"
type: docs
weight: 320
url: /ja/net/aspose.psd/rasterimage/getpixel/
---
{{< psd/tize >}}
## RasterImage.GetPixel method

画像のピクセルを取得します。パフォーマンス警告: すべての画像ピクセルを反復処理するためにこのメソッドを使用すると、重大なパフォーマンス問題が発生する可能性があります。より効率的なピクセル操作のためには、`LoadArgb32Pixels` メソッドを使用してピクセル配列全体を一度に取得してください。

```csharp
public Color GetPixel(int x, int y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | Int32 | ピクセルの X 位置。 |
| y | Int32 | ピクセルの Y 位置。 |

### 戻り値

指定された位置のピクセルの色です。

### 関連項目

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


