---
title: "TextRenderingHint 枚举"
type: docs
weight: 6340
url: /zh/python-net/aspose.psd/textrenderinghint/
---

指定文本渲染的质量。

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.TextRenderingHint

**Aspose.PSD Version:** 24.12.0

## **Members**
| **成员名称** | **Description** |
| :- | :- |
| ANTI_ALIAS | 每个字符使用其抗锯齿字形位图绘制，且不进行 hinting。由于抗锯齿，质量更好。由于关闭了 hinting，可能会注意到字干宽度差异。 |
| ANTI_ALIAS_GRID_FIT | 每个字符使用其带 hinting 的抗锯齿字形位图绘制。由于抗锯齿，质量大幅提升，但性能开销更高。 |
| CLEAR_TYPE_GRID_FIT | 每个字符使用其带 hinting 的 ClearType 字形位图绘制。最高质量设置。用于利用 ClearType 字体特性。 |
| SINGLE_BIT_PER_PIXEL | 每个字符使用其字形位图绘制。未使用 hinting。 |
| SINGLE_BIT_PER_PIXEL_GRID_FIT | 每个字符使用其字形位图绘制。使用 hinting 以改善字干和曲线上的字符外观。 |
| SYSTEM_DEFAULT | 每个字符使用其字形位图绘制，采用系统默认的渲染提示。文本将使用用户为系统选择的任何字体平滑设置进行绘制。 |
