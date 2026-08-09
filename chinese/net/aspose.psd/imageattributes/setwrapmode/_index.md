---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageAttributes 方法。设置用于决定如何在形状或形状边界上平铺纹理的包装模式。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。"
type: docs
weight: 210
url: /zh/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

```csharp
public void SetWrapMode(WrapMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | WrapMode | 一个 [`WrapMode`](../../wrapmode/) 元素，指定图像的重复副本如何用于平铺区域。 |

### 另请参阅

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | WrapMode | 一个 [`WrapMode`](../../wrapmode/) 元素，指定图像的重复副本如何用于平铺区域。 |
| color | Color | 一个 [`ImageAttributes`](../) 对象，指定渲染图像之外像素的颜色。如果 mode 参数设置为 Clamp 且传递给 DrawImage 的源矩形大于图像本身，则此颜色可见。 |

### 另请参阅

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

设置用于决定如何在形状上或形状边界处平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | WrapMode | 一个 [`WrapMode`](../../wrapmode/) 元素，指定图像的重复副本如何用于平铺区域。 |
| 颜色 | 颜色 | 一个颜色对象，指定渲染图像之外像素的颜色。如果 mode 参数设置为 Clamp 且传递给 DrawImage 的源矩形大于图像本身，则此颜色可见。 |
| 夹紧 | 布尔 | 此参数无效。请将其设为 false。 |

### 另请参阅

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


