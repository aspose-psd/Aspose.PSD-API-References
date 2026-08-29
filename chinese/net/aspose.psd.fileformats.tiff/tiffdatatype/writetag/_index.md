---
title: "TiffDataType.WriteTag"
second_title: "Aspose.PSD for .NET API 参考"
description: "TiffDataType 方法。写入标签数据"
type: docs
weight: 140
url: /zh/net/aspose.psd.fileformats.tiff/tiffdatatype/writetag/
---
{{< psd/tize >}}
## TiffDataType.WriteTag method

写入标签数据。

```csharp
public void WriteTag(TiffStreamWriter dataStream, long additionalDataOffset)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataStream | TiffStreamWriter | 数据流。 |
| additionalDataOffset | Int64 | 写入附加数据的偏移量。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 无法写入 + this.TagType + 的值；消息：+ exception.Message |

### 另请参阅

* class [TiffStreamWriter](../../../aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/)
* class [TiffDataType](../)
* namespace [Aspose.PSD.FileFormats.Tiff](../../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../../)


