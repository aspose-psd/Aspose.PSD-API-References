---
title: Enum CompressionMethod
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.CompressionMethod 列挙. 画像データに使用される圧縮方法を定義します
type: docs
weight: 1620
url: /ja/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

画像データに使用される圧縮方法を定義します。

```csharp
public enum CompressionMethod : short
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Raw | `0` | 圧縮なし。 RGBA 平面順序で raw バイトとして格納された画像データ. つまり、最初にすべての R データが書き込まれ、次にすべての G が書き込まれ、次にすべての B と最後にすべての A データが書き込まれます. |
| RLE | `1` | RLE 圧縮された画像データは、すべてのスキャン ライン (行 * チャネル) のバイト カウントで始まり、各 カウントが 2 バイト値として格納されます。 RLE 圧縮データが続き、各スキャン ラインが個別に圧縮されます。 RLE 圧縮は、Macintosh ROM ルーチン PackBits および TIFF 標準で使用される圧縮アルゴリズムと同じです。 |
| ZipWithoutPrediction | `2` | 予測なしの ZIP. |
| ZipWithPrediction | `3` | 予測付き ZIP. |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 組み立て [Aspose.PSD](../../)


