---
title: "StringFormatFlags 枚举"
type: docs
weight: 6300
url: /zh/python-net/aspose.psd/stringformatflags/
---

指定文本字符串的显示和布局信息。

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **成员名称** | **Description** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | 文本从右向左显示。 |
| DIRECTION_VERTICAL | 文本垂直对齐。 |
| DISPLAY_FORMAT_CONTROL | 诸如左到右标记等控制字符在输出中以代表性字形显示。 |
| EXACT_ALIGNMENT | 精确对齐，正确的填充 GDI+ |
| FIT_BLACK_BOX | 字符的部分可以超出字符串的布局矩形。默认情况下，字符会重新定位以避免任何超出。 |
| LINE_LIMIT | 仅在格式化矩形中布局完整的行。默认情况下，布局会一直进行，直到文本结束，或由于裁剪导致没有更多行可见，以先到者为准。<br/>            请注意，默认设置允许最后一行被格式化矩形部分遮挡，因为该矩形的高度可能不是行高的整数倍。为确保只显示完整的行，<br/>            请设置此值，并确保提供的格式化矩形高度至少等于一行的高度。 |
| MEASURE_TRAILING_SPACES | 包括每行末尾的尾随空格。默认情况下，MeasureString 方法返回的边界矩形不包含每行末尾的空格。设置此标志可在测量时包含该空格。 |
| NO_CLIP | 允许显示超出字形的部分以及超出格式化矩形的未换行文本。默认情况下，所有超出格式化矩形的文本和字形部分都会被裁剪。 |
| NO_FONT_FALLBACK | 已禁用对请求字体不支持的字符使用备用字体的回退。任何缺失的字符将显示为字体的缺失字形，通常是一个空方框。 |
| NO_WRAP | 在矩形内进行格式化时，行间的文本换行被禁用。当传入点而非矩形，或指定的矩形行长度为零时，会隐含此标志。 |
