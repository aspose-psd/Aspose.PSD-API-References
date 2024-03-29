---
title: Color.FromArgb
second_title: Aspose.PSD for .NET API 参考
description: Color 方法. 创建一个Color来自 32 位 ARGB 值的结构.
type: docs
weight: 1430
url: /zh/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

创建一个[`Color`](../)来自 32 位 ARGB 值的结构.

```csharp
public static Color FromArgb(int argb)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| argb | Int32 | 指定 32 位 ARGB 值的值。 |

### 返回值

这[`Color`](../)此方法创建的结构。

### 也可以看看

* struct [Color](../)
* 命名空间 [Aspose.PSD](../../color/)
* 部件 [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

创建一个[`Color`](../)来自四个 ARGB 分量（alpha、红色、绿色和蓝色）值的结构。虽然此方法允许为每个组件传递一个 32 位的值，但每个组件的值被限制为 8 位。

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| alpha | Int32 | 阿尔法分量。有效值为 0 到 255。 |
| red | Int32 | 红色成分。有效值为 0 到 255。 |
| green | Int32 | 绿色成分。有效值为 0 到 255。 |
| blue | Int32 | 蓝色成分。有效值为 0 到 255。 |

### 返回值

这[`Color`](../)该方法创建的。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* ， 或者*blue*小于 0 或大于 255。 |

### 也可以看看

* struct [Color](../)
* 命名空间 [Aspose.PSD](../../color/)
* 部件 [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

创建一个[`Color`](../)从指定的结构[`Color`](../)结构，但具有新指定的 alpha 值。尽管此方法允许为 alpha 值传递 32 位值，但该值被限制为 8 位。

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| alpha | Int32 | 新的 alpha 值[`Color`](../).有效值为 0 到 255。 |
| baseColor | Color | 这[`Color`](../)从中创建新的[`Color`](../). |

### 返回值

这[`Color`](../)该方法创建的。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*小于 0 或大于 255。 |

### 也可以看看

* struct [Color](../)
* 命名空间 [Aspose.PSD](../../color/)
* 部件 [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

创建一个[`Color`](../)来自指定 8 位颜色值（红色、绿色和蓝色）的结构。 alpha 值隐式为 255（完全不透明）。虽然此方法允许为每个颜色分量传递一个 32 位的值，但每个分量的值被限制为 8 位。

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| red | Int32 | 新的红色分量值[`Color`](../).有效值为 0 到 255。 |
| green | Int32 | 新的绿色组件值[`Color`](../).有效值为 0 到 255。 |
| blue | Int32 | 新的蓝色分量值[`Color`](../).有效值为 0 到 255。 |

### 返回值

这[`Color`](../)该方法创建的。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* ， 或者*blue*小于 0 或大于 255。 |

### 也可以看看

* struct [Color](../)
* 命名空间 [Aspose.PSD](../../color/)
* 部件 [Aspose.PSD](../../../)


