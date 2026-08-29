---
title: "枚举 StringFormatFlags"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.StringFormatFlags 枚举。指定文本字符串的显示和布局信息"
type: docs
weight: 6180
url: /zh/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

指定文本字符串的显示和布局信息。

```csharp
[Flags]
public enum StringFormatFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| DirectionRightToLeft | `1` | 文本从右向左显示。 |
| DirectionVertical | `2` | 文本垂直对齐。 |
| FitBlackBox | `4` | 字符的部分可以超出字符串的布局矩形。默认情况下，字符会重新定位以避免任何超出。 |
| DisplayFormatControl | `20` | 诸如从左到右标记之类的控制字符在输出中以代表性字形显示。 |
| NoFontFallback | `400` | 已禁用对请求字体不支持的字符回退到备用字体。任何缺失的字符将使用字体的缺失字形显示，通常是一个空方框。 |
| MeasureTrailingSpaces | `800` | 包括每行末尾的尾随空格。默认情况下，MeasureString 方法返回的边界矩形不包括每行末尾的空格。设置此标志可在测量时包含该空格。 |
| NoWrap | `1000` | 在矩形内进行格式化时，行之间的换行被禁用。当传入点而不是矩形，或指定的矩形行长度为零时，会隐含此标志。 |
| LineLimit | `2000` | 仅在格式化矩形中布局完整的行。默认情况下，布局会持续到文本结束，或直到由于裁剪而没有更多行可见，以先到者为准。请注意，默认设置允许最后一行被格式化矩形部分遮挡（该矩形的高度不是行高的整数倍）。为确保只显示完整的行，请指定此值，并确保提供的格式化矩形高度至少等于一行的高度。 |
| NoClip | `4000` | 允许显示超出矩形的字形悬挂部分和未换行的文本。默认情况下，所有超出格式化矩形的文本和字形部分都会被裁剪。 |
| ExactAlignment | `8000` | 精确对齐，正确的填充 GDI+ |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


