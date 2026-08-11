---
title: "Region.IsVisible"
second_title: "Aspose.PSD for .NET API Reference"
description: "Region メソッド。指定された点がこの Region に含まれているかテストします。"
type: docs
weight: 100
url: /ja/net/aspose.psd/region/isvisible/
---
{{< psd/tize >}}
## IsVisible(float, float) {#isvisible_11}

指定された点がこの [`Region`](../) に含まれているかテストします。

```csharp
public bool IsVisible(float x, float y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | シングル | テストする点の x 座標です。 |
| y | シングル | テストする点の y 座標です。 |

### 戻り値

指定された点がこの [`Region`](../) に含まれている場合は true、そうでない場合は false。

### 関連項目

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF) {#isvisible_2}

指定された [`PointF`](../../pointf/) 構造体がこの [`Region`](../) に含まれているかテストします。

```csharp
public bool IsVisible(PointF point)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | PointF | テスト対象の [`PointF`](../../pointf/) 構造体。 |

### 戻り値

*point* がこの [`Region`](../) に含まれている場合は true、そうでない場合は false。

### 関連項目

* struct [PointF](../../pointf/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

指定された [`Graphics`](../../graphics/) を使用して描画した場合に、指定された点がこの [`Region`](../) に含まれているかテストします。

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | シングル | テストする点の x 座標です。 |
| y | シングル | テストする点の y 座標です。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

指定された点がこの [`Region`](../) に含まれている場合は true、そうでない場合は false。

### 関連項目

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

指定された [`Graphics`](../../graphics/) を使用して描画した場合に、指定された [`PointF`](../../pointf/) 構造体がこの [`Region`](../) に含まれているかテストします。

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | PointF | テスト対象の [`PointF`](../../pointf/) 構造体。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

*point* がこの [`Region`](../) に含まれている場合は true、そうでない場合は false。

### 関連項目

* struct [PointF](../../pointf/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

指定された矩形の任意の部分がこの [`Region`](../) に含まれているかテストします。

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | シングル | テスト対象の矩形の左上隅の x 座標。 |
| y | シングル | テスト対象の矩形の左上隅の y 座標。 |
| width | シングル | テスト対象の矩形の幅。 |
| height | シングル | テスト対象の矩形の高さ。 |

### 戻り値

指定された矩形の一部でもこの[`Region`](../)オブジェクトに含まれる場合は true、そうでない場合は false。

### 関連項目

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

指定された[`RectangleF`](../../rectanglef/)構造体の一部がこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(RectangleF rect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | RectangleF | テスト対象の[`RectangleF`](../../rectanglef/)構造体。 |

### 戻り値

*rect* の一部でもこの[`Region`](../)に含まれる場合は true、そうでない場合は false。

### 関連項目

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

指定された矩形の一部が、指定された[`Graphics`](../../graphics/)で描画されたときにこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | シングル | テスト対象の矩形の左上隅の x 座標。 |
| y | シングル | テスト対象の矩形の左上隅の y 座標。 |
| width | シングル | テスト対象の矩形の幅。 |
| height | シングル | テスト対象の矩形の高さ。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

指定された矩形の一部でもこの[`Region`](../)に含まれる場合は true、そうでない場合は false。

### 関連項目

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

指定された[`RectangleF`](../../rectanglef/)構造体の一部が、指定された[`Graphics`](../../graphics/)で描画されたときにこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | RectangleF | テスト対象の[`RectangleF`](../../rectanglef/)構造体。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

*rect* がこの[`Region`](../)に含まれる場合は true、そうでない場合は false。

### 関連項目

* struct [RectangleF](../../rectanglef/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

指定された点が、指定された[`Graphics`](../../graphics/)オブジェクトで描画されたときにこの[`Region`](../)オブジェクトに含まれているかテストします。

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | Int32 | テストする点の x 座標です。 |
| y | Int32 | テストする点の y 座標です。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

指定された点がこの[`Region`](../)に含まれる場合は true、そうでない場合は false。

### 関連項目

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point) {#isvisible}

指定された[`Point`](../../point/)構造体がこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(Point point)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | Point | テスト対象の[`Point`](../../point/)構造体。 |

### 戻り値

*point* がこの [`Region`](../) に含まれている場合は true、そうでない場合は false。

### 関連項目

* struct [Point](../../point/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

指定された[`Point`](../../point/)構造体が、指定された[`Graphics`](../../graphics/)で描画されたときにこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(Point point, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | Point | テスト対象の[`Point`](../../point/)構造体。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

*point* がこの [`Region`](../) に含まれている場合は true、そうでない場合は false。

### 関連項目

* struct [Point](../../point/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

指定された矩形の任意の部分がこの [`Region`](../) に含まれているかテストします。

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | Int32 | テスト対象の矩形の左上隅の x 座標。 |
| y | Int32 | テスト対象の矩形の左上隅の y 座標。 |
| width | Int32 | テスト対象の矩形の幅。 |
| height | Int32 | テスト対象の矩形の高さ。 |

### 戻り値

指定された矩形の一部でもこの[`Region`](../)に含まれる場合は true、そうでない場合は false。

### 関連項目

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

指定された[`Rectangle`](../../rectangle/)構造体の一部がこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(Rectangle rect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | テスト対象の[`Rectangle`](../../rectangle/)構造体。 |

### 戻り値

このメソッドは、*rect* の一部でもこの[`Region`](../)に含まれる場合は true、そうでない場合は false を返します。

### 関連項目

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

指定された矩形の一部が、指定された[`Graphics`](../../graphics/)で描画されたときにこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | Int32 | テスト対象の矩形の左上隅の x 座標。 |
| y | Int32 | テスト対象の矩形の左上隅の y 座標。 |
| width | Int32 | テスト対象の矩形の幅。 |
| height | Int32 | テスト対象の矩形の高さ。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

指定された矩形の一部でもこの[`Region`](../)に含まれる場合は true、そうでない場合は false。

### 関連項目

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

指定された[`Rectangle`](../../rectangle/)構造体の一部が、指定された[`Graphics`](../../graphics/)で描画されたときにこの[`Region`](../)に含まれているかテストします。

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | テスト対象の[`Rectangle`](../../rectangle/)構造体。 |
| g | Graphics | グラフィックス コンテキストを表す [`Graphics`](../../graphics/)。 |

### 戻り値

*rect* の一部でもこの[`Region`](../)に含まれる場合は true、そうでない場合は false。

### 関連項目

* struct [Rectangle](../../rectangle/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


