---
title: "Graphics.FillPie"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。RectangleF 構造体で指定された楕円と 2 本の放射線によって定義されたパイセクションの内部を塗りつぶします。"
type: docs
weight: 380
url: /ja/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

楕円で指定された [`RectangleF`](../../rectanglef/) 構造体と2本の放射線で定義されたパイセクションの内部を塗りつぶします。

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 構造体は、パイセクションが生成される楕円を定義する外接矩形を表します。 |
| startAngle | シングル | x 軸からパイセクションの第一側まで、時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータからパイセクションの第二側まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

楕円で指定された [`RectangleF`](../../rectanglef/) 構造体と2本の放射線で定義されたパイセクションの内部を塗りつぶします。

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 構造体は、パイセクションが生成される楕円を定義する外接矩形を表します。 |
| startAngle | シングル | x 軸からパイセクションの第一側まで、時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータからパイセクションの第二側まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

座標ペア、幅、高さ、2本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| x | シングル | パイセクションが生成される楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | シングル | パイセクションが生成される楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | シングル | パイセクションが生成される楕円を定義する外接矩形の幅です。 |
| height | シングル | パイセクションが生成される楕円を定義する外接矩形の高さです。 |
| startAngle | シングル | x 軸からパイセクションの第一側まで、時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータからパイセクションの第二側まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

座標ペア、幅、高さ、2本の放射線で指定された楕円で定義されたパイセクションの内部を塗りつぶします。

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) は塗りの特性を決定します。 |
| x | Int32 | パイセクションが生成される楕円を定義する外接矩形の左上隅の x 座標です。 |
| y | Int32 | パイセクションが生成される楕円を定義する外接矩形の左上隅の y 座標です。 |
| width | Int32 | パイセクションが生成される楕円を定義する外接矩形の幅です。 |
| height | Int32 | パイセクションが生成される楕円を定義する外接矩形の高さです。 |
| startAngle | Int32 | x 軸からパイセクションの第一側まで、時計回りに測定した角度（度）です。 |
| sweepAngle | Int32 | *startAngle* パラメータからパイセクションの第二側まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。 |

### 関連項目

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


