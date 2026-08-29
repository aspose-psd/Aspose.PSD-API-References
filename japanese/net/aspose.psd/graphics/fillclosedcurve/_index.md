---
title: "Graphics.FillClosedCurve"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。PointF 構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトの張力 0.5 と Alternate 塗りつぶしモードを使用します。"
type: docs
weight: 350
url: /ja/net/aspose.psd/graphics/fillclosedcurve/
---
{{< psd/tize >}}
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

[`PointF`](../../pointf/)構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトの張力 0.5 と Alternate 塗りつぶしモードを使用します。

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| points | PointF[] | スプラインを定義する [`PointF`](../../pointf/) 構造体の配列です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *points* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

[`PointF`](../../pointf/)構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードで塗りつぶします。このメソッドはデフォルトの張力 0.5 を使用します。

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| points | PointF[] | スプラインを定義する [`PointF`](../../pointf/) 構造体の配列です。 |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 列挙体のメンバーで、曲線の塗りつぶし方法を決定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *points* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

[`PointF`](../../pointf/)構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードと張力で塗りつぶします。

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は、塗りつぶしの特性を決定します。 |
| points | PointF[] | スプラインを定義する [`PointF`](../../pointf/) 構造体の配列です。 |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 列挙体のメンバーで、曲線の塗りつぶし方法を決定します。 |
| テンション | シングル | 曲線のテンションを指定する、0.0F 以上の値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *points* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

[`Point`](../../point/)構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を塗りつぶします。このメソッドはデフォルトの張力 0.5 と Alternate 塗りつぶしモードを使用します。

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| points | Point[] | スプラインを定義する[`Point`](../../point/)構造体の配列。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *points* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

[`Point`](../../point/)構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードで塗りつぶします。このメソッドはデフォルトの張力 0.5 を使用します。

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| points | Point[] | スプラインを定義する[`Point`](../../point/)構造体の配列。 |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 列挙体のメンバーで、曲線の塗りつぶし方法を決定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *points* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

[`Point`](../../point/)構造体の配列で定義された閉じたカーディナルスプライン曲線の内部を、指定された塗りつぶしモードと張力で塗りつぶします。

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| points | Point[] | スプラインを定義する[`Point`](../../point/)構造体の配列。 |
| fillmode | FillMode | [`FillMode`](../../fillmode/) 列挙体のメンバーで、曲線の塗りつぶし方法を決定します。 |
| テンション | シングル | 曲線のテンションを指定する、0.0F 以上の値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *points* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


