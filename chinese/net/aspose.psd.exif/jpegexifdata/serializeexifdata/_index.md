---
title: "JpegExifData.SerializeExifData"
second_title: "Aspose.PSD for .NET API 参考"
description: "JpegExifData 方法。序列化 EXIF 数据。写入标签的值和内容。最影响大小的标签是缩略图标签内容"
type: docs
weight: 270
url: /zh/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
{{< psd/tize >}}
## JpegExifData.SerializeExifData method

序列化 EXIF 数据。写入标签的值和内容。最具影响力的尺寸标签是缩略图标签的内容。

```csharp
public byte[] SerializeExifData()
```

### 返回值

序列化的 EXIF 数据。

## 备注

整体段大小必须小于或等于 MaxExifSegmentSize 字节，以生成正确的 jpeg 图像。提示：如果 EXIF 部分大小过大，请尝试减小缩略图尺寸或更改其压缩方式。

### 另请参阅

* class [JpegExifData](../)
* namespace [Aspose.PSD.Exif](../../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../../)


