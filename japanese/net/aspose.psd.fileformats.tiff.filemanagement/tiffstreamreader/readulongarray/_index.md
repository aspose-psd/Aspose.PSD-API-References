---
title: TiffStreamReader.ReadULongArray
second_title: Aspose.PSD for .NET API リファレンス
description: TiffStreamReader 方法. ストリームから符号なし整数値の配列を読み取ります
type: docs
weight: 200
url: /ja/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
## TiffStreamReader.ReadULongArray method

ストリームから符号なし整数値の配列を読み取ります。

```csharp
public uint[] ReadULongArray(long position, long count)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| position | Int64 | 読み取る位置。 |
| count | Int64 | 要素は重要です。 |

### 戻り値

符号なし整数値の配列。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | count;総バイト数が負です。 + カウント + x4= + 総バイト数 |

### 関連項目

* class [TiffStreamReader](../)
* 名前空間 [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* 組み立て [Aspose.PSD](../../../)


