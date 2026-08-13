---
title: "CompressionMethod 枚举"
type: docs
weight: 2410
url: /zh/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

定义用于图像数据的压缩方法。

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **成员名称** | **Description** |
| :- | :- |
| RAW | 无压缩。图像数据以 RGBA 平面顺序存储为原始字节。<br/>            这意味着首先写入所有 R 数据，然后写入所有 G 数据，接着是所有 B 数据，最后写入所有 A 数据。 |
| RLE | RLE 压缩的图像数据以所有扫描线（行 * 通道）的字节计数开始，每个<br/>计数存储为两个字节的值。随后是 RLE 压缩的数据，每条扫描线单独压缩。<br/>RLE 压缩使用与 Macintosh ROM 例程 PackBits 和 TIFF 标准相同的压缩算法。 |
| ZIP_WITH_PREDICTION | ZIP 未使用预测。 |
| ZIP_WITH_PREDICTION | ZIP 使用预测。 |
