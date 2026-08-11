---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。指定された PointF 構造体の配列を通って基数スプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。"
type: docs
weight: 210
url: /ja/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

指定された [`PointF`](../../pointf/) 構造体の配列を通って基数スプラインを描画します。このメソッドはデフォルトのテンション 0.5 を使用します。

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、および高さを決定します。 |
| points | PointF[] | スプラインを定義する [`PointF`](../../pointf/) 構造体の配列です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

指定されたテンションを使用して、指定された [`PointF`](../../pointf/) 構造体の配列を通って基数スプラインを描画します。

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、および高さを決定します。 |
| points | PointF[] | 曲線を定義する点を表す [`PointF`](../../pointf/) 構造体の配列です。 |
| テンション | シングル | 曲線のテンションを指定する、0.0F 以上の値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

指定された [`PointF`](../../pointf/) 構造体の配列を通って基数スプラインを描画します。描画は配列の先頭からオフセットして開始されます。このメソッドはデフォルトのテンション 0.5 を使用します。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、および高さを決定します。 |
| points | PointF[] | スプラインを定義する [`PointF`](../../pointf/) 構造体の配列です。 |
| offset | Int32 | *points* パラメータの配列の最初の要素から曲線の開始点までのオフセットです。 |
| numberOfSegments | Int32 | 曲線の開始点の後に含めるセグメント数です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

指定されたテンションを使用して、指定された [`PointF`](../../pointf/) 構造体の配列を通って基数スプラインを描画します。描画は配列の先頭からオフセットして開始されます。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、および高さを決定します。 |
| points | PointF[] | スプラインを定義する [`PointF`](../../pointf/) 構造体の配列です。 |
| offset | Int32 | *points* パラメータの配列の最初の要素から曲線の開始点までのオフセットです。 |
| numberOfSegments | Int32 | 曲線の開始点の後に含めるセグメント数です。 |
| テンション | シングル | 曲線のテンションを指定する、0.0F 以上の値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

指定された [`Point`](../../point/) 構造体の配列を通って基数スプラインを描画します。

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、および高さを決定します。 |
| points | Point[] | スプラインを定義する[`Point`](../../point/)構造体の配列。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

指定された張力を使用して、指定された[`Point`](../../point/)構造体の配列を通るカーディナルスプラインを描画します。

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、および高さを決定します。 |
| points | Point[] | スプラインを定義する[`Point`](../../point/)構造体の配列。 |
| テンション | シングル | 曲線のテンションを指定する、0.0F 以上の値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

指定された張力を使用して、指定された[`Point`](../../point/)構造体の配列を通るカーディナルスプラインを描画します。

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、および高さを決定します。 |
| points | Point[] | スプラインを定義する[`Point`](../../point/)構造体の配列。 |
| offset | Int32 | *points* パラメータの配列の最初の要素から曲線の開始点までのオフセットです。 |
| numberOfSegments | Int32 | 曲線の開始点の後に含めるセグメント数です。 |
| テンション | シングル | 曲線のテンションを指定する、0.0F 以上の値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


