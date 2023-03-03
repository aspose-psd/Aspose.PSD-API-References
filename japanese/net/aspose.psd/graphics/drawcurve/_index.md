---
title: Graphics.DrawCurve
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. の指定された配列を介してカーディナル スプラインを描画しますPointF構造この方法ではデフォルトのテンション 0.5. を使用します
type: docs
weight: 200
url: /ja/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../../pointf/)構造。この方法では、デフォルトのテンション 0.5. を使用します。

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、高さを決定します。 |
| points | PointF[] | の配列[`PointF`](../../pointf/)スプラインを定義する構造。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../../pointf/)指定された張力を使用する構造.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、高さを決定します。 |
| points | PointF[] | の配列[`PointF`](../../pointf/)曲線を定義する点を表す構造。 |
| tension | Single | 曲線の張力を指定する 0.0F 以上の値。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../../pointf/)構造。描画は、配列の先頭からのオフセットで開始されます. この方法では、デフォルトのテンション 0.5 を使用します.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、高さを決定します。 |
| points | PointF[] | の配列[`PointF`](../../pointf/)スプラインを定義する構造。 |
| offset | Int32 | の配列の最初の要素からのオフセット*points*パラメータをカーブの始点に移動します。 |
| numberOfSegments | Int32 | 曲線に含める始点の後のセグメントの数。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

の指定された配列を介してカーディナル スプラインを描画します。[`PointF`](../../pointf/)指定された張力を使用する構造。描画は配列の先頭からのオフセットで始まります.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、高さを決定します。 |
| points | PointF[] | の配列[`PointF`](../../pointf/)スプラインを定義する構造。 |
| offset | Int32 | の配列の最初の要素からのオフセット*points*パラメータをカーブの始点に移動します。 |
| numberOfSegments | Int32 | 曲線に含める始点の後のセグメントの数。 |
| tension | Single | 曲線の張力を指定する 0.0F 以上の値。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

の指定された配列を介してカーディナル スプラインを描画します。[`Point`](../../point/)構造物.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、高さを決定します。 |
| points | Point[] | の配列[`Point`](../../point/)スプラインを定義する構造。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

の指定された配列を介してカーディナル スプラインを描画します。[`Point`](../../point/)指定された張力を使用する構造.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、高さを決定します。 |
| points | Point[] | の配列[`Point`](../../point/)スプラインを定義する構造。 |
| tension | Single | 曲線の張力を指定する 0.0F 以上の値。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

の指定された配列を介してカーディナル スプラインを描画します。[`Point`](../../point/)指定された張力を使用する構造.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、高さを決定します。 |
| points | Point[] | の配列[`Point`](../../point/)スプラインを定義する構造。 |
| offset | Int32 | の配列の最初の要素からのオフセット*points*パラメータをカーブの始点に移動します。 |
| numberOfSegments | Int32 | 曲線に含める始点の後のセグメントの数。 |
| tension | Single | 曲線の張力を指定する 0.0F 以上の値。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)


