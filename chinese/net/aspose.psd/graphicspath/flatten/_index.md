---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD for .NET API 参考"
description: "GraphicsPath 方法。将此路径中的每条曲线转换为一系列相连的线段"
type: docs
weight: 90
url: /zh/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

将此路径中的每条曲线转换为一系列相连的线段。

```csharp
public void Flatten()
```

### 另请参阅

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

应用指定的变换，然后将此 [`GraphicsPath`](../) 中的每条曲线转换为一系列相连的线段。

```csharp
public void Flatten(Matrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | 用于在扁平化之前变换此 [`GraphicsPath`](../) 的 [`Matrix`](../../matrix/)。 |

### 另请参阅

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

将此 [`GraphicsPath`](../) 中的每条曲线转换为一系列相连的线段。

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | Matrix | 用于在扁平化之前变换此 [`GraphicsPath`](../) 的 [`Matrix`](../../matrix/)。 |
| 平滑度 | 单精度 | 指定曲线与其扁平化近似之间允许的最大误差。默认值为 0.25。降低平整度值会增加近似中的线段数量。 |

### 另请参阅

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


