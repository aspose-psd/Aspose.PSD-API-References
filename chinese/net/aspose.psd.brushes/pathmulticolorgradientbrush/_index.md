---
title: Class PathMulticolorGradientBrush
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Brushes.PathMulticolorGradientBrush 班级. 封装了一个Brush具有渐变的对象此类不能被继承
type: docs
weight: 190
url: /zh/net/aspose.psd.brushes/pathmulticolorgradientbrush/
---
## PathMulticolorGradientBrush class

封装了一个[`Brush`](../../aspose.psd/brush/)具有渐变的对象。此类不能被继承。

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor)(GraphicsPath) | 初始化一个新的实例`PathMulticolorGradientBrush`具有指定路径的类. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_1)(PointF[]) | 初始化一个新的实例`PathMulticolorGradientBrush`具有指定点的类. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_3)(Point[]) | 初始化一个新的实例`PathMulticolorGradientBrush`具有指定点的类. |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_2)(PointF[], WrapMode) | 初始化一个新的实例`PathMulticolorGradientBrush`具有指定点和包装模式的类。 |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush/#constructor_4)(Point[], WrapMode) | 初始化一个新的实例`PathMulticolorGradientBrush`具有指定点和包装模式的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 获取构建此画笔的图形路径。 |
| [InterpolationColors](../../aspose.psd.brushes/pathmulticolorgradientbrush/interpolationcolors/) { get; set; } | 获取或设置一个[`ColorBlend`](../../aspose.psd/colorblend/)定义多色线性渐变. |
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

### 也可以看看

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 部件 [Aspose.PSD](../../)


