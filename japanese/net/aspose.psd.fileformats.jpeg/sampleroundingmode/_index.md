---
title: Enum SampleRoundingMode
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode 列挙. n ビット値を 8 ビット値に変換する方法を定義します
type: docs
weight: 1530
url: /ja/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

n ビット値を 8 ビット値に変換する方法を定義します。

```csharp
public enum SampleRoundingMode
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Extrapolate | `0` | 8 ビット値を外挿して n ビットに適合させます。ここで、1 &lt; n &lt; 8. 可能なすべての 8 ビット値の数は 1 &lt;&lt; 8 = 256 で、0 から 255 までです。 すべての可能な値の数n ビット値は 1 &lt;&lt; n、0 から (1 &lt;&lt; n) - 1. 8 ビット値 V8 に対応する最も妥当な n ビット値 Vn は、Vn = V8 &gt;&gt; (8 - n)。 |
| Truncate | `1` | 8 ビット値を切り捨てて n ビットに合わせます。ここで、1 &lt; n &lt; 8. 可能なすべての n ビット値の数は、0 から (1 &lt;&lt; n) - 1 までの 1 &lt;&lt; n です。 8 ビット値 V8 に対応する最も妥当な n ビット値 Vn は、Vn = V8 &amp; ((1 &lt;&lt; n) - 1). と等しくなります。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* 組み立て [Aspose.PSD](../../)


