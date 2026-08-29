---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD for .NET API 参考"
description: "TiffStreamReader 方法。读取来自流的有符号整数值数组"
type: docs
weight: 140
url: /zh/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

从流中读取有符号整数数组。

```csharp
public int[] ReadSLongArray(long position, long count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位置 | Int64 | 读取的位置。 |
| count | Int64 | 元素计数。 |

### 返回值

有符号整数值的数组。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | count;总字节计数为负。+ count + x4= + totalBytes |

### 另请参阅

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


