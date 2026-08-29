---
title: "列挙体 CompressionMethod"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod 列挙体。画像データに使用される圧縮方法を定義します。"
type: docs
weight: 1630
url: /ja/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

画像データに使用される圧縮方式を定義します。

```csharp
public enum CompressionMethod : short
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Raw | `0` | 圧縮なし。画像データは RGBA 平面順の生バイトとして保存されます。つまり、最初にすべての R データが書き込まれ、次にすべての G、続いて B、最後にすべての A データが書き込まれます。 |
| RLE | `1` | RLE 圧縮された画像データは、すべてのスキャンライン（行 × チャネル）のバイト数で始まり、各カウントは 2 バイトの値として格納されます。その後に RLE 圧縮データが続き、各スキャンラインは個別に圧縮されます。RLE 圧縮は、Macintosh ROM ルーチン PackBits および TIFF 標準で使用される圧縮アルゴリズムと同じです。 |
| ZipWithoutPrediction | `2` | 予測なしの ZIP。 |
| ZipWithPrediction | `3` | 予測付き ZIP。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


