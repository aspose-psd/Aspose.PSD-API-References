---
title: Enum StringFormatFlags
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.StringFormatFlags 枚举. 指定文本字符串的显示和布局信息
type: docs
weight: 5680
url: /zh/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

指定文本字符串的显示和布局信息。

```csharp
[Flags]
public enum StringFormatFlags
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| DirectionRightToLeft | `1` | 文本从右到左显示。 |
| DirectionVertical | `2` | 文本垂直对齐。 |
| FitBlackBox | `4` | 允许部分字符悬垂在字符串的布局矩形上。默认情况下，字符会重新定位以避免任何悬垂。 |
| DisplayFormatControl | `20` | 控制字符（例如从左到右的标记）在输出中显示为具有代表性的字形。 |
| NoFontFallback | `400` | 已禁用为请求的字体中不支持的字符回退到备用字体。任何缺失的字符都显示为缺失字形的字体，通常是一个空心方块。 |
| MeasureTrailingSpaces | `800` | 包括每行末尾的尾随空格。默认情况下，MeasureString 方法返回的边界矩形不包括每行末尾的空格。设置此标志以在 measurement. 中包含该空间 |
| NoWrap | `1000` | 禁用矩形内格式化时行间文本换行。当一个点而不是一个矩形被传递时，或者当指定的矩形具有零线长度时，这个标志是隐含的。 |
| LineLimit | `2000` | 只有整行布局在格式矩形中。默认情况下，布局一直持续到文本末尾，或者直到由于裁剪而不再显示任何行，以先到者为准。 请注意，默认设置允许最后一行被非格式矩形部分遮挡行高的整数倍。为确保只显示整行， 指定此值并注意提供至少与一行高度一样高的格式化矩形。 |
| NoClip | `4000` | 允许显示字形的悬垂部分和延伸到格式化矩形之外的展开文本。默认情况下，所有到达格式化矩形之外的文本和字形部分都被剪掉。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


