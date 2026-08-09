---
title: "类 Font"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Font 类。定义文本的特定格式，包括字体大小和样式属性。此类不可被继承。"
type: docs
weight: 4750
url: /zh/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

定义文本的特定格式，包括字体、大小和样式属性。此类不可继承。

```csharp
public sealed class Font
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | 初始化一个使用指定现有 `Font` 和 [`FontStyle`](../fontstyle/) 枚举的新 `Font`。 |
| [Font](font/#constructor_1)(string, float) | 使用指定的大小初始化一个新 `Font`。字符集设置为 Default，图形单位设置为 Point，字体样式设置为 Regular。 |
| [Font](font/#constructor_2)(string, float, FontStyle) | 使用指定的大小和样式初始化一个新 `Font`。字符集设置为 Default，图形单位设置为 Point。 |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | 使用指定的大小和单位初始化一个新 `Font`。字符集设置为 Default，样式设置为 Regular。 |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | 使用指定的大小、样式和单位初始化一个新 `Font`。 |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | 使用指定的大小、样式、单位和字符集初始化一个新 `Font`。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | 获取一个值，指示此 `Font` 是否为粗体。 |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | 获取一个字节值，指定此 `Font` 使用的字符集。 |
| [Italic](../../aspose.psd/font/italic/) { get; } | 获取一个值，指示此 `Font` 是否为斜体。 |
| [Name](../../aspose.psd/font/name/) { get; } | 获取此 `Font` 的字体名称。 |
| [Size](../../aspose.psd/font/size/) { get; } | 获取此 `Font` 的 em 大小，单位由 [`Unit`](./unit/) 属性指定。 |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | 获取一个值，指示此 `Font` 是否指定在字体上绘制水平线。 |
| [Style](../../aspose.psd/font/style/) { get; } | 获取此 `Font` 的样式信息。 |
| [Underline](../../aspose.psd/font/underline/) { get; } | 获取一个值，指示此 `Font` 是否带下划线。 |
| [Unit](../../aspose.psd/font/unit/) { get; } | 获取此 `Font` 的计量单位。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | 创建此 `Font` 的精确深度复制。 |
| override [Equals](../../aspose.psd/font/equals/)(object) | 指示指定的对象是否为 `Font` 且具有与此 `Font` 相同的属性值。 |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | 获取此 `Font` 的哈希码。 |
| override [ToString](../../aspose.psd/font/tostring/)() | 返回此 `Font` 的可读字符串表示。 |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


