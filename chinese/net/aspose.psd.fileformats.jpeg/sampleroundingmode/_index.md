---
title: Enum SampleRoundingMode
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode 枚举. 定义将 n 位值转换为 8 位值的方法
type: docs
weight: 1530
url: /zh/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

定义将 n 位值转换为 8 位值的方法。

```csharp
public enum SampleRoundingMode
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Extrapolate | `0` | 外推一个8位值使其适合n位，其中1 &lt; n &lt; 8. 所有可能的8位值的个数为1 &lt;&lt; 8 = 256，从0到255. 所有可能的个数n位值为1 &lt;&lt; n，从0到(1 &lt;&lt; n) - 1. 某8位值V8对应的最合理的n位值Vn等于Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | 截断一个 8 位值以使其适合 n 位，其中 1 &lt; n &lt; 8. 所有可能的 n 位值的数量为 1 &lt;&lt; n，从 0 到 (1 &lt;&lt; n) - 1. 对应于某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* 部件 [Aspose.PSD](../../)


