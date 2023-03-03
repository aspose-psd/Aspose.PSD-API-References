---
title: Class TextureBrush
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Brushes.TextureBrush 班级. 的每个属性TextureBrush班级是Brush使用图像填充形状内部的对象此类不能被继承
type: docs
weight: 210
url: /zh/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

的每个属性`TextureBrush`班级是[`Brush`](../../aspose.psd/brush/)使用图像填充形状内部的对象。此类不能被继承。

```csharp
public sealed class TextureBrush : TransformBrush
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | 初始化一个新的实例`TextureBrush`使用指定图像的类。 |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | 初始化一个新的实例`TextureBrush`使用指定图像和边界矩形的类。 |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | 初始化一个新的实例`TextureBrush`使用指定图像和边界矩形的类。 |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | 初始化一个新的实例`TextureBrush`使用指定图像和环绕模式的类。 |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | 初始化一个新的实例`TextureBrush`使用指定图像、边界矩形和图像属性的类。 |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | 初始化一个新的实例`TextureBrush`使用指定图像、边界矩形和图像属性的类。 |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | 初始化一个新的实例`TextureBrush`使用指定图像、环绕模式和边界矩形的类。 |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | 初始化一个新的实例`TextureBrush`使用指定图像、环绕模式和边界矩形的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | 获取[`Image`](../../aspose.psd/image/)与此关联的对象`TextureBrush`对象. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | 获取[`ImageAttributes`](./imageattributes/)与此有关`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | 获取[`Rectangle`](../../aspose.psd/rectangle/)与此有关`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取指示转换是否以某种方式更改的值。例如设置转换矩阵或 调用任何改变转换矩阵的方法。引入该属性是为了向后兼容 GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值为 0 表示画笔完全可见，值为 1 表示画笔完全不透明。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | 获取或设置副本[`Matrix`](../../aspose.psd/matrix/)为此定义了局部几何变换[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | 获取或设置一个[`WrapMode`](../../aspose.psd/wrapmode/)指示此包装模式的枚举[`TransformBrush`](../transformbrush/) . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 创建当前的新深度克隆[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | 乘以[`Matrix`](../../aspose.psd/matrix/)表示这个的局部几何变换[`LinearGradientBrush`](../lineargradientbrush/)由指定的[`Matrix`](../../aspose.psd/matrix/)通过预先指定[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 乘以[`Matrix`](../../aspose.psd/matrix/)表示这个的局部几何变换[`LinearGradientBrush`](../lineargradientbrush/)由指定的[`Matrix`](../../aspose.psd/matrix/)按指定顺序. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | 重置[`Transform`](../transformbrush/transform/)属性到身份. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 按指定量旋转局部几何变换。此方法将旋转添加到 transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 按指定顺序按指定量旋转局部几何变换。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到 transform. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 按指定顺序按指定数量缩放局部几何变换。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 按指定尺寸平移局部几何变换。此方法将翻译添加到 transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 按指定顺序按指定尺寸平移局部几何变换。 |

### 也可以看看

* class [TransformBrush](../transformbrush/)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 部件 [Aspose.PSD](../../)


