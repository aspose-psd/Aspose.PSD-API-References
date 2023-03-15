---
title: Class Font
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Font 班级. 定义文本的特定格式包括字体大小和样式属性此类不能被继承
type: docs
weight: 4280
url: /zh/net/aspose.psd/font/
---
## Font class

定义文本的特定格式，包括字体、大小和样式属性。此类不能被继承。

```csharp
public sealed class Font
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | 初始化一个新的`Font`使用指定的现有`Font`和[`FontStyle`](../fontstyle/)枚举. |
| [Font](font/#constructor_1)(string, float) | 初始化一个新的`Font`使用指定的大小。字符集设置为Default 图形单位Point 字体样式为Regular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | 初始化一个新的`Font`使用指定的尺寸和样式。字符集设置为Default 图形单位Point . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | 初始化一个新的`Font`使用指定的大小和单位。字符集设置为Default，样式设置为Regular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | 初始化一个新的`Font`使用指定的大小、样式和单位。 |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | 初始化一个新的`Font`使用指定的大小、样式、单位和字符集。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | 获取一个值，指示是否这`Font`是粗体. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | 获取指定字符集的字节值`Font`使用. |
| [Italic](../../aspose.psd/font/italic/) { get; } | 获取一个值，指示是否这`Font`是斜体. |
| [Name](../../aspose.psd/font/name/) { get; } | 获取这个的人脸名称`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | 获取 this 的 em-size`Font`以指定的单位衡量[`Unit`](./unit/)财产. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | 获取一个值，指示是否这`Font`指定一条穿过字体的水平线。 |
| [Style](../../aspose.psd/font/style/) { get; } | 获取此样式信息`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | 获取一个值，指示是否这`Font`有下划线. |
| [Unit](../../aspose.psd/font/unit/) { get; } | 获取这个的度量单位`Font` . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | 创建一个精确的深拷贝`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | 表示指定的对象是否是一个`Font`并且具有与此相同的属性值`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | 获取这个的哈希码`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | 返回一个人类可读的字符串表示形式`Font` . |

### 例子

此示例演示了使用 Font 和 SolidBrush 类在 Image 表面上绘制字符串。该示例创建一个新图像并使用 Figures 和 GraphicsPath 绘制形状

```csharp
[C#]

//创建图像实例
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //创建并初始化Graphics类的实例
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //清除图形表面
    graphics.Clear(Color.Wheat);

    //创建字体实例
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

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


