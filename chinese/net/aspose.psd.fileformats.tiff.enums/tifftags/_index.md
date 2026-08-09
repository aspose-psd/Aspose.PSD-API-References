---
title: "TiffTags 枚举"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags 枚举。tiff 标签枚举"
type: docs
weight: 4640
url: /zh/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

tiff 标记枚举。

```csharp
public enum TiffTags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| SubFileType | `254` | 子文件数据描述符。 |
| OsubfileType | `255` | [已被 TIFF rev. 5.0 废弃] 子文件中的数据类型。 |
| ImageWidth | `256` | 图像宽度（像素）。 |
| ImageLength | `257` | 图像高度（像素）。 |
| BitsPerSample | `258` | 每通道位数（样本）。 |
| Compression | `259` | 数据压缩技术。 |
| Photometric | `262` | 光度解释。 |
| Thresholding | `263` | [已被 TIFF rev. 5.0 废弃] 对数据使用的阈值处理。 |
| CellWidth | `264` | [已被 TIFF rev. 5.0 废弃] 抖动矩阵宽度。 |
| CellLength | `265` | [已被 TIFF rev. 5.0 废弃] 抖动矩阵高度。 |
| FillOrder | `266` | 字节内的数据顺序。 |
| DocumentName | `269` | 保存图像的文档名称。 |
| ImageDescription | `270` | 图像信息。 |
| Make | `271` | 扫描仪制造商名称。 |
| Model | `272` | 扫描仪型号名称/编号。 |
| StripOffsets | `273` | 数据条带的偏移量。 |
| Orientation | `274` | [已被 TIFF rev. 5.0 弃用] 图像方向。 |
| SamplesPerPixel | `277` | 每像素采样数。 |
| RowsPerStrip | `278` | 每条数据的行数。 |
| StripByteCounts | `279` | 条带的字节计数。 |
| MinSampleValue | `280` | [已被 TIFF rev. 5.0 弃用] 最小采样值。 |
| MaxSampleValue | `281` | [已被 TIFF rev. 5.0 弃用] 最大采样值。 |
| Xresolution | `282` | X 方向像素/分辨率。 |
| Yresolution | `283` | Y 方向像素/分辨率。 |
| PlanarConfig | `284` | 存储组织方式。 |
| PageName | `285` | 图像来源的页面名称。 |
| Xposition | `286` | 图像左侧的 X 页面偏移。 |
| Yposition | `287` | 图像左侧的 Y 页面偏移。 |
| FreeOffsets | `288` | [已被 TIFF rev. 5.0 弃用] 指向空闲块的字节偏移。 |
| FreeByteCounts | `289` | [已被 TIFF rev. 5.0 弃用] 空闲块的大小。 |
| GrayResponseUnit | `290` | [已被 TIFF rev. 6.0 弃用] 灰度曲线精度。 |
| GrayResponseCurve | `291` | [已被 TIFF rev. 6.0 弃用] 灰度响应曲线。 |
| T4Options | `292` | TIFF 6.0 对 GROUP3OPTIONS 的正式别名。CCITT 第三组传真编码的选项。32 位标志位。 |
| T6Options | `293` | CCITT 第四组传真编码的选项。32 位标志位。TIFF 6.0 对 GROUP4OPTIONS 的正式别名。 |
| ResolutionUnit | `296` | 分辨率的单位。 |
| PageNumber | `297` | 多页的页码。 |
| ColorResponseUnit | `300` | [已被 TIFF rev. 6.0 弃用] 色彩曲线精度。 |
| TransferFunction | `301` | 色度计信息。 |
| Software | `305` | 名称 &amp; 发布。 |
| DateTime | `306` | 创建日期和时间。 |
| Artist | `315` | 图像创建者。 |
| HostComputer | `316` | 创建所在的机器。 |
| Predictor | `317` | 使用 LZW 的预测方案。 |
| WhitePoint | `318` | 图像白点。 |
| PrimaryChromaticities | `319` | 主要色度。 |
| ColorMap | `320` | 调色板图像的 RGB 映射。 |
| HalftoneHints | `321` | 高光 + 阴影信息。 |
| TileWidth | `322` | 瓦片宽度（像素）。 |
| TileLength | `323` | 瓦片高度（像素）。 |
| TileOffsets | `324` | 数据瓦片的偏移量。 |
| TileByteCounts | `325` | 瓦片的字节计数。 |
| BadFaxLines | `326` | 像素计数错误的行。 |
| CleanFaxData | `327` | 重新生成的行信息。 |
| ConsecutiveBadFaxLines | `328` | 最大连续错误行数。 |
| SubIfd | `330` | 子图像描述符。 |
| InkSet | `332` | 分离图像中的墨水。 |
| InkNames | `333` | 墨水的 ASCII 名称。 |
| NumberOfInks | `334` | 墨水数量。 |
| DotRange | `336` | 0% 和 100% 点代码。 |
| TargetPrinter | `337` | 分离目标。 |
| ExtraSamples | `338` | 关于额外样本的信息。 |
| SampleFormat | `339` | 数据样本格式。 |
| SminSampleValue | `340` | 变量 MinSampleValue。 |
| SmaxSampleValue | `341` | 变量 MaxSampleValue。 |
| TransferRange | `342` | 变量 TransferRange |
| ClipPath | `343` | ClipPath。由 Adobe TIFF technote 2 在 TIFF 版本 6.0 之后引入。 |
| Xclippathunits | `344` | XClipPathUnits。由 Adobe TIFF technote 2 在 TIFF 版本 6.0 之后引入。 |
| Yclippathunits | `345` | YClipPathUnits。由 Adobe TIFF technote 2 在 TIFF 版本 6.0 之后引入。 |
| Indexed | `346` | Indexed。由 Adobe TIFF Technote 3 在 TIFF 版本 6.0 之后引入。 |
| JpegTables | `347` | JPEG 表流。于 TIFF 版本 6.0 之后引入。 |
| OpiProxy | `351` | OPI Proxy。由 Adobe TIFF technote 在 TIFF 版本 6.0 之后引入。 |
| JpegProc | `512` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] JPEG 处理算法。 |
| JpegInerchangeFormat | `513` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] 指向 SOI 标记的指针。 |
| JpegInterchangeFormatLength | `514` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] JFIF 流长度 |
| JpegRestartInterval | `515` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] 重启间隔长度。 |
| JpegLosslessPredictors | `517` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] 无损过程预测器。 |
| JpegPointTransform | `518` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] 无损点变换。 |
| JpegQTables | `519` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] Q 矩阵偏移。 |
| JpegDCtables | `520` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] DCT 表偏移。 |
| JpegACtables | `521` | [已废弃，由 Technical Note #2 指定的修订 JPEG-in-TIFF 方案] AC 系数偏移。 |
| YcbcrCoefficients | `529` | RGB → YCbCr 变换。 |
| YcbcrSubSampling | `530` | YCbCr 子采样因子。 |
| YcbcrPositioning | `531` | 子采样定位。 |
| ReferenceBlackWhite | `532` | 色度计信息。 |
| XmlPacket | `700` | XML 包。由 Adobe XMP Specification 于 2004 年 1 月在 TIFF 版本 6.0 之后引入。 |
| OpiImageid | `32781` | OPI ImageID。由 Adobe TIFF technote 在 TIFF 版本 6.0 之后引入。 |
| Refpts | `32953` | 图像参考点。私有标签已注册到 Island Graphics。 |
| Copyright | `33432` | 版权字符串。此标签列在 TIFF rev. 6.0 中，所有权未知。 |
| PhotoshopResources | `34377` | Photoshop 图像资源。 |
| IccProfile | `34675` | 嵌入的 ICC 设备配置文件 |
| ExifIfdPointer | `34665` | 指向 Exif IFD 的指针。 |
| XPTitle | `40091` | 关于图像的信息，供 Windows Explorer 使用。如果存在 ImageDescription 标签，Windows Explorer 将忽略 XPTitle。 |
| XPComment | `40092` | 图像注释，供 Windows Explorer 使用。 |
| XPAuthor | `40093` | 图像作者，供 Windows Explorer 使用。如果存在 Artist 标签，Windows Explorer 将忽略 XPAuthor。 |
| XPKeywords | `40094` | 图像关键字，供 Windows Explorer 使用。 |
| XPSubject | `40095` | 主题图像，供 Windows Explorer 使用。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


