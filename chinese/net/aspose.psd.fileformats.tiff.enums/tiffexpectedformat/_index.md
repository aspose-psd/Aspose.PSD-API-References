---
title: "枚举 TiffExpectedFormat"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat 枚举。期望的 tiff 文件格式"
type: docs
weight: 4540
url: /zh/net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/
---
{{< psd/tize >}}
## TiffExpectedFormat enumeration

预期的 tiff 文件格式。

```csharp
public enum TiffExpectedFormat
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 默认的 tiff 格式是不压缩，仅使用 B/W 1 位每像素的格式。您也可以使用此设置获取空选项，并使用您的标签或其他设置进行初始化。 |
| TiffLzwBw | `1` | 使用 LZW 压缩且仅为 B/W 1 位每像素格式的 tiff。 |
| TiffLzwRgb | `2` | 使用 LZW 压缩且为 RGB 彩色格式的 tiff。 |
| TiffLzwRgba | `3` | 使用 LZW 压缩且为带透明度的 RGBA 彩色格式的 tiff。 |
| TiffLzwCmyk | `4` | 使用 LZW 压缩的 CMYK tiff |
| TiffCcittFax3 | `5` | 使用 CCITT FAX3 编码的 tiff。仅支持该方案的 B/W 1 位每像素。 |
| TiffCcittFax4 | `6` | 使用 CCITT FAX4 编码的 tiff。仅支持该方案的 B/W 1 位每像素。 |
| TiffDeflateBw | `7` | 使用 deflate 压缩且仅为 B/W 1 位每像素格式的 tiff。 |
| TiffDeflateRgb | `8` | 具有 Deflate 压缩和 RGB 颜色格式的 tiff。 |
| TiffDeflateRgba | `9` | 具有 Deflate 压缩和 RGBA 颜色格式的 tiff。 |
| TiffCcitRle | `10` | tiff 使用 CCITT RLE 编码。仅支持该方案的 B/W 每像素 1 位。 |
| TiffJpegRgb | `11` | 具有 Jpeg 压缩和 RGB 颜色格式的 tiff。 |
| TiffJpegYCbCr | `12` | 具有 Jpeg 压缩和 YCBCR 颜色格式的 tiff。 |
| TiffNoCompressionBw | `13` | 未压缩的 tiff，仅支持 B/W 每像素 1 位的格式。 |
| TiffNoCompressionRgb | `14` | 未压缩的 tiff，RGB 颜色格式。 |
| TiffNoCompressionRgba | `15` | 未压缩的 tiff，带透明度的 RGBA 颜色格式。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


