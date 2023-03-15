---
title: Class PathGradientBrushBase
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Brushes.PathGradientBrushBase 班级. 代表一个Brush具有基本路径梯度功能.
type: docs
weight: 180
url: /zh/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

代表一个[`Brush`](../../aspose.psd/brush/)具有基本路径梯度功能.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 获取构建此画笔的图形路径。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取指示转换是否以某种方式更改的值。例如设置转换矩阵或 调用任何改变转换矩阵的方法。引入该属性是为了向后兼容 GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值为 0 表示画笔完全可见，值为 1 表示画笔完全不透明。 |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | 获取此画笔所基于的路径点。 |
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

### 评论

请注意，在创建`PathGradientBrushBase`类至少应该用2点初始化。内部路径 created 永远是一个封闭的图形，最后一个点连接第一个点。那个形状充满了这个`PathGradientBrushBase`. GDI+ 实现抛出一个OutOfMemoryException当传入具有相同坐标的空数组或点集时。 `PathGradientBrushBase`当点数组包含少于 2 个点时抛出异常，ArgumentException is 抛出而不是OutOfMemoryException当 points 数组不可接受时。 中心点默认计算为传入点的质心。用户可以稍后更改此点。 默认情况下，焦点比例为空点 (0.0, 0.0)。

### 也可以看看

* class [TransformBrush](../transformbrush/)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 部件 [Aspose.PSD](../../)


