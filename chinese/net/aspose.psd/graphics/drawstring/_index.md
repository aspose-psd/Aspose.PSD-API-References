---
title: DrawString
second_title: Aspose.PSD for .NET API 参考
description: 使用指定的Brushaspose.psd/brush和Fontaspose.psd/font在指定位置绘制指定文本字符串对象
type: docs
weight: 320
url: /zh/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

使用指定的[`Brush`](../../brush)和[`Font`](../../font)在指定位置绘制指定文本字符串对象。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)确定绘制文本的颜色和纹理。 |
| x | Single | 绘制文本左上角的 x 坐标。 |
| y | Single | 绘制文本左上角的 y 坐标。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 - 或 - *s*为空。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

使用指定的[`Brush`](../../brush)和[`Font`](../../font)在指定位置绘制指定文本字符串对象。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)确定绘制文本的颜色和纹理。 |
| point | PointF | [`PointF`](../../pointf)结构，指定绘制文本的左上角。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 - 或 - *s*为空。 |

### 例子

这个例子演示了使用 Font 和 SolidBrush 类在图像表面上绘制字符串。该示例使用 Figures 和 GraphicsPath

```csharp
[C#]

//创建一个Image实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化一个Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //创建一个字体实例
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //创建一个具有红色的 SolidBrush 实例
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //画一个字符串
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 创建导出选项。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 保存所有更改
    image.Save("C:\\temp\\output.gif", options);
}
```

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

使用指定的[`Brush`](../../brush)和[`Font`](../../font)在指定位置绘制指定文本字符串使用指定[`StringFormat`](../../stringformat)的格式化属性的对象。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)确定绘制文本的颜色和纹理。 |
| x | Single | 绘制文本左上角的 x 坐标。 |
| y | Single | 绘制文本左上角的 y 坐标。 |
| format | StringFormat | [`StringFormat`](../../stringformat)指定应用于绘制文本的格式属性，例如行间距和对齐方式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 - 或 - *s*为空。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

使用指定的[`Brush`](../../brush)和[`Font`](../../font)在指定位置绘制指定文本字符串使用指定[`StringFormat`](../../stringformat)的格式化属性的对象。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)确定绘制文本的颜色和纹理。 |
| point | PointF | [`PointF`](../../pointf)结构，指定绘制文本的左上角。 |
| format | StringFormat | [`StringFormat`](../../stringformat)指定应用于绘制文本的格式属性，例如行间距和对齐方式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 - 或 - *s*为空。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

使用指定的[`Brush`](../../brush)和[`Font`](../../font)在指定的矩形中绘制指定的文本字符串对象。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)确定绘制文本的颜色和纹理。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef)结构，指定绘制文本的位置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 - 或 - *s*为空。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

使用指定的[`Brush`](../../brush)和[`Font`](../../font)在指定的矩形中绘制指定的文本字符串使用指定[`StringFormat`](../../stringformat)的格式化属性的对象。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | String | 要绘制的字符串。 |
| font | Font | [`Font`](../../font)定义字符串的文本格式。 |
| brush | Brush | [`Brush`](../../brush)确定绘制文本的颜色和纹理。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef)结构，指定绘制文本的位置。 |
| format | StringFormat | [`StringFormat`](../../stringformat)指定应用于绘制文本的格式属性，例如行间距和对齐方式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *brush*为空。 - 或 - *s*为空。 - 或 - *brush*为空。 |

### 也可以看看

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
