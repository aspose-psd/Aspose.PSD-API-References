---
title: "Region.Equals"
second_title: "Aspose.PSD for .NET API 参考"
description: "Region 方法。测试指定的 Region 在指定绘图表面上是否与此 Region 相同"
type: docs
weight: 40
url: /zh/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

测试指定的 [`Region`](../) 在指定绘图表面上是否与此 [`Region`](../) 相同。

```csharp
public bool Equals(Region region, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | Region | 要测试的 [`Region`](../)。 |
| g | Graphics | 一个表示绘图表面的 [`Graphics`](../../graphics/)。 |

### 返回值

如果在应用与 *g* 参数关联的变换时区域的内部与此区域的内部相同，则为 True；否则为 false。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *g *or* region* 为 null。 |

### 另请参阅

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

检查对象是否相等。

```csharp
public override bool Equals(object obj)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | Object | 另一个对象。 |

### 返回值

相等比较的结果。

### 另请参阅

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


