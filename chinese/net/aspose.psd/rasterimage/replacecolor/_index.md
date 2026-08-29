---
title: "RasterImage.ReplaceColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "RasterImage 方法。将一种颜色替换为另一种颜色，允许一定差异，并保留原始 alpha 值以保持平滑边缘"
type: docs
weight: 460
url: /zh/net/aspose.psd/rasterimage/replacecolor/
---
{{< psd/tize >}}
## ReplaceColor(Color, byte, Color) {#replacecolor}

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

```csharp
public void ReplaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldColor | 颜色 | 要被替换的旧颜色。 |
| oldColorDiff | 字节 | 允许的旧颜色差异，以便扩大替换后颜色的色调范围。 |
| newColor | 颜色 | 用于替换旧颜色的新颜色。 |

### 另请参阅

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceColor(int, byte, int) {#replacecolor_1}

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

```csharp
public virtual void ReplaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldColorArgb | Int32 | 待替换的旧颜色 ARGB 值。 |
| oldColorDiff | 字节 | 允许的旧颜色差异，以便扩大替换后颜色的色调范围。 |
| newColorArgb | Int32 | 用于替换旧颜色的新颜色 ARGB 值。 |

### 另请参阅

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


