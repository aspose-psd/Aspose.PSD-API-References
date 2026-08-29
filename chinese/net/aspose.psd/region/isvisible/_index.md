---
title: "Region.IsVisible"
second_title: "Aspose.PSD for .NET API 参考"
description: "Region 方法。测试指定的点是否包含在此 Region 中。"
type: docs
weight: 100
url: /zh/net/aspose.psd/region/isvisible/
---
{{< psd/tize >}}
## IsVisible(float, float) {#isvisible_11}

测试指定的点是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(float x, float y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 单精度 | 要测试的点的 x 坐标。 |
| y | 单精度 | 要测试的点的 y 坐标。 |

### 返回值

当指定的点包含在此 [`Region`](../) 中时返回 true；否则返回 false。

### 另请参阅

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF) {#isvisible_2}

测试指定的 [`PointF`](../../pointf/) 结构是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(PointF point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | PointF | 要测试的 [`PointF`](../../pointf/) 结构。 |

### 返回值

当 *point* 包含在此 [`Region`](../) 中时返回 true；否则返回 false。

### 另请参阅

* struct [PointF](../../pointf/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

测试在使用指定的 [`Graphics`](../../graphics/) 绘制时，指定的点是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 单精度 | 要测试的点的 x 坐标。 |
| y | 单精度 | 要测试的点的 y 坐标。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当指定的点包含在此 [`Region`](../) 中时返回 true；否则返回 false。

### 另请参阅

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

测试在使用指定的 [`Graphics`](../../graphics/) 绘制时，指定的 [`PointF`](../../pointf/) 结构是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | PointF | 要测试的 [`PointF`](../../pointf/) 结构。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当 *point* 包含在此 [`Region`](../) 中时返回 true；否则返回 false。

### 另请参阅

* struct [PointF](../../pointf/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

测试指定矩形的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 单精度 | 要测试的矩形左上角的 x 坐标。 |
| y | 单精度 | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | 单精度 | 要测试的矩形的宽度。 |
| 高度 | 单精度 | 要测试的矩形的高度。 |

### 返回值

当指定矩形的任何部分包含在此 [`Region`](../) 对象中时为 true；否则为 false。

### 另请参阅

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

测试指定的 [`RectangleF`](../../rectanglef/) 结构的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(RectangleF rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | 要测试的 [`RectangleF`](../../rectanglef/) 结构。 |

### 返回值

当 *rect* 的任何部分包含在此 [`Region`](../) 中时为 true；否则为 false。

### 另请参阅

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

测试在使用指定的 [`Graphics`](../../graphics/) 绘制时，指定矩形的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | 单精度 | 要测试的矩形左上角的 x 坐标。 |
| y | 单精度 | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | 单精度 | 要测试的矩形的宽度。 |
| 高度 | 单精度 | 要测试的矩形的高度。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当指定矩形的任何部分包含在此 [`Region`](../) 中时为 true；否则为 false。

### 另请参阅

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

测试在使用指定的 [`Graphics`](../../graphics/) 绘制时，指定的 [`RectangleF`](../../rectanglef/) 结构的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | 要测试的 [`RectangleF`](../../rectanglef/) 结构。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当 *rect* 包含在此 [`Region`](../) 中时为 true；否则为 false。

### 另请参阅

* struct [RectangleF](../../rectanglef/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

测试在使用指定的 [`Graphics`](../../graphics/) 对象绘制时，指定点是否包含在此 [`Region`](../) 对象中。

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 要测试的点的 x 坐标。 |
| y | Int32 | 要测试的点的 y 坐标。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当指定点包含在此 [`Region`](../) 中时为 true；否则为 false。

### 另请参阅

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point) {#isvisible}

测试指定的 [`Point`](../../point/) 结构是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(Point point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | Point | 要测试的 [`Point`](../../point/) 结构。 |

### 返回值

当 *point* 包含在此 [`Region`](../) 中时返回 true；否则返回 false。

### 另请参阅

* struct [Point](../../point/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

测试在使用指定的 [`Graphics`](../../graphics/) 绘制时，指定的 [`Point`](../../point/) 结构是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(Point point, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | Point | 要测试的 [`Point`](../../point/) 结构。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当 *point* 包含在此 [`Region`](../) 中时返回 true；否则返回 false。

### 另请参阅

* struct [Point](../../point/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

测试指定矩形的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 要测试的矩形左上角的 x 坐标。 |
| y | Int32 | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | Int32 | 要测试的矩形的宽度。 |
| 高度 | Int32 | 要测试的矩形的高度。 |

### 返回值

当指定矩形的任何部分包含在此 [`Region`](../) 中时为 true；否则为 false。

### 另请参阅

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

测试指定的 [`Rectangle`](../../rectangle/) 结构的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(Rectangle rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 要测试的 [`Rectangle`](../../rectangle/) 结构。 |

### 返回值

当 *rect* 的任何部分包含在此 [`Region`](../) 中时，此方法返回 true；否则返回 false。

### 另请参阅

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

测试在使用指定的 [`Graphics`](../../graphics/) 绘制时，指定矩形的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 要测试的矩形左上角的 x 坐标。 |
| y | Int32 | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | Int32 | 要测试的矩形的宽度。 |
| 高度 | Int32 | 要测试的矩形的高度。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当指定矩形的任何部分包含在此 [`Region`](../) 中时为 true；否则为 false。

### 另请参阅

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

测试在使用指定的 [`Graphics`](../../graphics/) 绘制时，指定的 [`Rectangle`](../../rectangle/) 结构的任何部分是否包含在此 [`Region`](../) 中。

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 要测试的 [`Rectangle`](../../rectangle/) 结构。 |
| g | Graphics | 表示图形上下文的 [`Graphics`](../../graphics/)。 |

### 返回值

当 *rect* 的任何部分包含在此 [`Region`](../) 中时为 true；否则为 false。

### 另请参阅

* struct [Rectangle](../../rectangle/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


