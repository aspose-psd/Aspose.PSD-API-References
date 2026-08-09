---
title: "Color.FromArgb"
second_title: "Aspose.PSD for .NET API 参考"
description: "Color 方法。使用 32 位 ARGB 值创建 Color 结构"
type: docs
weight: 1430
url: /zh/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

从 32 位 ARGB 值创建一个 [`Color`](../) 结构。

```csharp
public static Color FromArgb(int argb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | Int32 | 一个指定 32 位 ARGB 值的值。 |

### 返回值

此方法创建的 [`Color`](../) 结构。

### 另请参阅

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

使用四个 ARGB 分量（alpha、red、green 和 blue）值创建一个 [`Color`](../) 结构。虽然此方法允许为每个分量传入 32 位值，但每个分量的值限制为 8 位。

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | Int32 | alpha 分量。有效值范围为 0 到 255。 |
| 红色 | Int32 | 红色分量。有效值范围为 0 到 255。 |
| 绿色 | Int32 | 绿色分量。有效值范围为 0 到 255。 |
| 蓝色 | Int32 | 蓝色分量。有效值范围为 0 到 255。 |

### 返回值

此方法创建的 [`Color`](../)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*、*red*、*green* 或 *blue* 小于 0 或大于 255。 |

### 另请参阅

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

从指定的 [`Color`](../) 结构创建一个 [`Color`](../) 结构，但使用新的指定 alpha 值。虽然此方法允许为 alpha 值传入 32 位值，但该值限制为 8 位。

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alpha | Int32 | 新 [`Color`](../) 的 alpha 值。有效值范围为 0 到 255。 |
| baseColor | Color | 用于创建新 [`Color`](../) 的 [`Color`](../)。 |

### 返回值

此方法创建的 [`Color`](../)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 小于 0 或大于 255。 |

### 另请参阅

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

从指定的 8 位颜色值（红、绿、蓝）创建一个 [`Color`](../) 结构。alpha 值隐式为 255（完全不透明）。虽然此方法允许为每个颜色分量传入 32 位值，但每个分量的值限制为 8 位。

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| red | Int32 | 新 [`Color`](../) 的红色分量值。有效值范围为 0 到 255。 |
| green | Int32 | 新 [`Color`](../) 的绿色分量值。有效值范围为 0 到 255。 |
| blue | Int32 | 新 [`Color`](../) 的蓝色分量值。有效值范围为 0 到 255。 |

### 返回值

此方法创建的 [`Color`](../)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *red*、*green* 或 *blue* 小于 0 或大于 255。 |

### 另请参阅

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


