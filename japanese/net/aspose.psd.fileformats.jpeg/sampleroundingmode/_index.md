---
title: "列挙体 SampleRoundingMode"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode 列挙体。nビット値を8ビット値に変換する方法を定義します。"
type: docs
weight: 1540
url: /ja/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

nビット値が8ビット値に変換される方法を定義します。

```csharp
public enum SampleRoundingMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Extrapolate | `0` | 8ビット値を n ビットに合わせて外挿します（1 < n < 8）。可能なすべての8ビット値の数は 1 << 8 = 256 で、0 から 255 です。可能なすべての n ビット値の数は 1 << n で、0 から (1 << n) - 1 です。ある8ビット値 V8 に対応する最も妥当な n ビット値 Vn は Vn = V8 >> (8 - n) と等しくなります。 |
| Truncate | `1` | 8ビット値を n ビットに合わせて切り捨てます（1 < n < 8）。可能なすべての n ビット値の数は 1 << n で、0 から (1 << n) - 1 です。ある8ビット値 V8 に対応する最も妥当な n ビット値 Vn は Vn = V8 & ((1 << n) - 1) と等しくなります。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


