---
title: Enum TextRenderingHint
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.TextRenderingHint 枚举. 指定文本呈现的质量
type: docs
weight: 5700
url: /zh/net/aspose.psd/textrenderinghint/
---
## TextRenderingHint enumeration

指定文本呈现的质量。

```csharp
public enum TextRenderingHint
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| SystemDefault | `0` | 每个字符都是使用其字形位图绘制的，带有系统默认渲染提示。将使用用户为系统选择的任何字体平滑设置绘制文本。 |
| SingleBitPerPixelGridFit | `1` | 每个字符都是使用其字形位图绘制的。提示用于改善字干和曲率的字符外观。 |
| SingleBitPerPixel | `2` | 每个字符都是使用其字形位图绘制的。未使用提示。 |
| AntiAliasGridFit | `3` | 每个字符都是使用其带提示的抗锯齿字形位图绘制的。由于抗锯齿，质量更好，但性能成本更高。 |
| AntiAlias | `4` | 每个字符都是使用其抗锯齿字形位图绘制的，没有提示。由于抗锯齿，质量更好。词干宽度差异可能会很明显，因为提示已关闭。 |
| ClearTypeGridFit | `5` | 每个字符都是使用带有提示的字形 ClearType 位图绘制的。最高质量的设置。用于利用 ClearType 字体功能。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


