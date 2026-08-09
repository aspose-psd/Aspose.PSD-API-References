---
title: "枚举 SampleRoundingMode"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode 枚举。定义将 n 位值转换为 8 位值的方式。"
type: docs
weight: 1540
url: /zh/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

定义了一种将 n 位值转换为 8 位值的方式。

```csharp
public enum SampleRoundingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Extrapolate | `0` | 将 8 位值外推以适配 n 位，其中 1 &lt; n &lt; 8。所有可能的 8 位值数量为 1 &lt;&lt; 8 = 256，范围从 0 到 255。所有可能的 n 位值数量为 1 &lt;&lt; n，范围从 0 到 (1 &lt;&lt; n) - 1。对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 &gt;&gt; (8 - n)。 |
| Truncate | `1` | 将 8 位值截断以适配 n 位，其中 1 &lt; n &lt; 8。所有可能的 n 位值数量为 1 &lt;&lt; n，范围从 0 到 (1 &lt;&lt; n) - 1。对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 &amp; ((1 &lt;&lt; n) - 1)。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


