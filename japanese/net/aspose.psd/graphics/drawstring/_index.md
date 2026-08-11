---
title: "Graphics.DrawString"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。指定された Brush と Font オブジェクトを使用して、指定された位置に指定されたテキスト文字列を描画します。"
type: docs
weight: 330
url: /ja/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

指定された位置に、指定された [`Brush`](../../brush/) と [`Font`](../../font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | 文字列 | 描画する文字列。 |
| font | Font | [`Font`](../../font/) は文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/) は描画されたテキストの色とテクスチャを決定します。 |
| x | シングル | 描画されたテキストの左上隅の x 座標。 |
| y | シングル | 描画されたテキストの左上隅の y 座標。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *s* が null です。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

指定された位置に、指定された [`Brush`](../../brush/) と [`Font`](../../font/) オブジェクトを使用して、指定されたテキスト文字列を描画します。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | 文字列 | 描画する文字列。 |
| font | Font | [`Font`](../../font/) は文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/) は描画されたテキストの色とテクスチャを決定します。 |
| point | PointF | [`PointF`](../../pointf/) 構造体は描画されたテキストの左上隅を指定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *s* が null です。 |

## 例

この例では、Font クラスと SolidBrush クラスを使用して Image 表面に文字列を描画する方法を示します。例では新しい Image を作成し、Figures と GraphicsPath を使用して図形を描画します。

```csharp
[C#]

//Image のインスタンスを作成します
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics クラスのインスタンスを作成し、初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスをクリアします
    graphics.Clear(Color.Wheat);

    //Font のインスタンスを作成します
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //赤色の SolidBrush のインスタンスを作成します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //文字列を描画します
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // エクスポート オプションを作成します。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.gif", options);
}
```

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

指定された [`StringFormat`](../../stringformat/) の書式属性を使用して、指定された位置に、指定された [`Brush`](../../brush/) と [`Font`](../../font/) オブジェクトで指定されたテキスト文字列を描画します。

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | 文字列 | 描画する文字列。 |
| font | Font | [`Font`](../../font/) は文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/) は描画されたテキストの色とテクスチャを決定します。 |
| x | シングル | 描画されたテキストの左上隅の x 座標。 |
| y | シングル | 描画されたテキストの左上隅の y 座標。 |
| format | StringFormat | [`StringFormat`](../../stringformat/) は描画されたテキストに適用される行間や配置などの書式属性を指定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *s* が null です。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

指定された [`StringFormat`](../../stringformat/) の書式属性を使用して、指定された位置に、指定された [`Brush`](../../brush/) と [`Font`](../../font/) オブジェクトで指定されたテキスト文字列を描画します。

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | 文字列 | 描画する文字列。 |
| font | Font | [`Font`](../../font/) は文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/) は描画されたテキストの色とテクスチャを決定します。 |
| point | PointF | [`PointF`](../../pointf/) 構造体は描画されたテキストの左上隅を指定します。 |
| format | StringFormat | [`StringFormat`](../../stringformat/) は描画されたテキストに適用される行間や配置などの書式属性を指定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *s* が null です。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

指定された矩形内に、指定された [`Brush`](../../brush/) と [`Font`](../../font/) オブジェクトで指定されたテキスト文字列を描画します。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | 文字列 | 描画する文字列。 |
| font | Font | [`Font`](../../font/) は文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/) は描画されたテキストの色とテクスチャを決定します。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) 構造体は描画されたテキストの位置を指定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *s* が null です。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

指定された [`StringFormat`](../../stringformat/) の書式属性を使用して、指定された矩形内に、指定された [`Brush`](../../brush/) と [`Font`](../../font/) オブジェクトで指定されたテキスト文字列を描画します。

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | 文字列 | 描画する文字列。 |
| font | Font | [`Font`](../../font/) は文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/) は描画されたテキストの色とテクスチャを決定します。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) 構造体は描画されたテキストの位置を指定します。 |
| format | StringFormat | [`StringFormat`](../../stringformat/) は描画されたテキストに適用される行間や配置などの書式属性を指定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* が null です。-or- *s* が null です。-or- *brush* が null です。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


