---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD for .NET API Reference"
description: "TiffStreamReader メソッド。ストリームから 符号付き integer 値の配列を読み取ります。"
type: docs
weight: 140
url: /ja/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

ストリームから符号付き整数値の配列を読み取ります。

```csharp
public int[] ReadSLongArray(long position, long count)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 位置 | Int64 | 読み取り位置です。 |
| カウント | Int64 | 要素数です。 |

### 戻り値

符号付き integer 値の配列です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | count;合計バイト数が負です。 + count + x4= + totalBytes |

### 関連項目

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


