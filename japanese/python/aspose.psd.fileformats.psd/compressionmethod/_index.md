---
title: "CompressionMethod 列挙体"
type: docs
weight: 2410
url: /ja/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

画像データに使用される圧縮方法を定義します。

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **メンバー名** | **説明** |
| :- | :- |
| RAW | 圧縮なし。画像データは RGBA の平面順序で生バイトとして保存されます。<br/>            つまり、最初にすべての R データが書き込まれ、次に G、次に B、最後に A データが書き込まれます。 |
| RLE | RLE 圧縮された画像データは、すべてのスキャンライン（行 * チャネル）のバイト数から始まり、各<br/>            カウントは2バイトの値として格納されます。RLE 圧縮データが続き、各スキャンラインは個別に圧縮されます。<br/>            RLE 圧縮は、Macintosh ROM ルーチン PackBits と TIFF 標準で使用されているのと同じ圧縮アルゴリズムです。 |
| ZIP_WITHOUT_PREDICTION | ZIP 予測なし。 |
| ZIP_WITH_PREDICTION | ZIP 予測あり。 |
