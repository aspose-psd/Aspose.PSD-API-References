---
title: "Graphics.DrawString"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。使用指定的 Brush 和 Font 对象在指定位置绘制指定的文本字符串"
type: docs
weight: 330
url: /zh/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font/) 定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush/) 决定已绘制文本的颜色和纹理。 |
| x | 单精度 | 已绘制文本左上角的 x 坐标。 |
| y | 单精度 | 已绘制文本左上角的 y 坐标。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参阅

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font/) 定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush/) 决定已绘制文本的颜色和纹理。 |
| point | PointF | [`PointF`](../../pointf/) 结构，指定已绘制文本的左上角。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

## 示例

此示例演示了使用 Font 和 SolidBrush 类在 Image 表面上绘制字符串。示例创建了一个新 Image 并使用 Figures 和 GraphicsPath 绘制形状。

```csharp
[C#]

//创建 Image 的实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化 Graphics 类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除 Graphics 表面
    graphics.Clear(Color.Wheat);

    //创建 Font 的实例
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //创建具有红色的 SolidBrush 实例
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //绘制字符串
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 创建导出选项。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 保存所有更改
    image.Save("C:\\temp\\output.gif", options);
}
```

### 另请参阅

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象，并使用指定的 [`StringFormat`](../../stringformat/) 的格式属性绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font/) 定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush/) 决定已绘制文本的颜色和纹理。 |
| x | 单精度 | 已绘制文本左上角的 x 坐标。 |
| y | 单精度 | 已绘制文本左上角的 y 坐标。 |
| format | StringFormat | [`StringFormat`](../../stringformat/) 指定格式属性（如行间距和对齐方式），这些属性将应用于已绘制的文本。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参阅

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

在指定位置使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象，并使用指定的 [`StringFormat`](../../stringformat/) 的格式属性绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font/) 定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush/) 决定已绘制文本的颜色和纹理。 |
| point | PointF | [`PointF`](../../pointf/) 结构，指定已绘制文本的左上角。 |
| format | StringFormat | [`StringFormat`](../../stringformat/) 指定格式属性（如行间距和对齐方式），这些属性将应用于已绘制的文本。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参阅

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

在指定矩形内使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font/) 定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush/) 决定已绘制文本的颜色和纹理。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) 结构，指定已绘制文本的位置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。 |

### 另请参阅

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

在指定矩形内使用指定的 [`Brush`](../../brush/) 和 [`Font`](../../font/) 对象，并使用指定的 [`StringFormat`](../../stringformat/) 的格式属性绘制指定的文本字符串。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font/) 定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush/) 决定已绘制文本的颜色和纹理。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) 结构，指定已绘制文本的位置。 |
| format | StringFormat | [`StringFormat`](../../stringformat/) 指定格式属性（如行间距和对齐方式），这些属性将应用于已绘制的文本。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。-or- *s* 为 null。-or- *brush* 为 null。 |

### 另请参阅

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


