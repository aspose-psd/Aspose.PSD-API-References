---
title: "枚举 CompressionMethod"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod 枚举。定义用于图像数据的压缩方法"
type: docs
weight: 1630
url: /zh/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

定义用于图像数据的压缩方法。

```csharp
public enum CompressionMethod : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Raw | `0` | 无压缩。图像数据以 RGBA 平面顺序的原始字节存储。这意味着首先写入所有 R 数据，然后是所有 G 数据，接着是所有 B 数据，最后写入所有 A 数据。 |
| RLE | `1` | RLE 压缩的图像数据以所有扫描线（行 * 通道）的字节计数开始，每个计数以两个字节存储。随后是 RLE 压缩的数据，每条扫描线单独压缩。RLE 压缩使用的算法与 Macintosh ROM 例程 PackBits 以及 TIFF 标准使用的压缩算法相同。 |
| ZipWithoutPrediction | `2` | ZIP（无预测）。 |
| ZipWithPrediction | `3` | ZIP（有预测）。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


