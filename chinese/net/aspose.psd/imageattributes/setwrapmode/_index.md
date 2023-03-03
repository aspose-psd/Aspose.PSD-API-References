---
title: ImageAttributes.SetWrapMode
second_title: Aspose.PSD for .NET API 参考
description: ImageAttributes 方法. 设置用于决定如何在形状上或在形状边界处平铺纹理的环绕模式当纹理小于它正在填充的形状时纹理会平铺在形状上以填充它
type: docs
weight: 210
url: /zh/net/aspose.psd/imageattributes/setwrapmode/
---
## SetWrapMode(WrapMode) {#setwrapmode}

设置用于决定如何在形状上或在形状边界处平铺纹理的环绕模式。当纹理小于它正在填充的形状时，纹理会平铺在形状上以填充它。

```csharp
public void SetWrapMode(WrapMode mode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mode | WrapMode | 的一个元素[`WrapMode`](../../wrapmode/)指定图像的重复副本如何用于平铺区域。 |

### 也可以看看

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* 命名空间 [Aspose.PSD](../../imageattributes/)
* 部件 [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

设置用于决定如何在形状上或在形状边界处平铺纹理的环绕模式和颜色。当纹理小于它正在填充的形状时，纹理会平铺在形状上以填充它。

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mode | WrapMode | 的一个元素[`WrapMode`](../../wrapmode/)指定图像的重复副本如何用于平铺区域。 |
| color | Color | 一个[`ImageAttributes`](../)指定渲染图像外像素颜色的对象。如果模式参数设置为，则此颜色可见Clamp并且传递给 DrawImage 的源矩形比图像本身大。 |

### 也可以看看

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* 命名空间 [Aspose.PSD](../../imageattributes/)
* 部件 [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

设置用于决定如何在形状上或在形状边界处平铺纹理的环绕模式和颜色。当纹理小于它正在填充的形状时，纹理会平铺在形状上以填充它。

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mode | WrapMode | 的一个元素[`WrapMode`](../../wrapmode/)指定图像的重复副本如何用于平铺区域。 |
| color | Color | 指定渲染图像外部像素颜色的颜色对象。如果模式参数设置为，则此颜色可见Clamp并且传递给 DrawImage 的源矩形比图像本身大。 |
| clamp | Boolean | 此参数无效。将其设置为假。 |

### 也可以看看

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* 命名空间 [Aspose.PSD](../../imageattributes/)
* 部件 [Aspose.PSD](../../../)


