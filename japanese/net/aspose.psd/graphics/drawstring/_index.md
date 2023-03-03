---
title: Graphics.DrawString
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. 指定した位置に指定した文字列を指定した文字列で描画しますBrushとFontオブジェクト.
type: docs
weight: 320
url: /ja/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../../brush/)と[`Font`](../../font/)オブジェクト.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| s | String | 描画する文字列。 |
| font | Font | [`Font`](../../font/)文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/)描画されるテキストの色とテクスチャを決定します。 |
| x | Single | 描画されたテキストの左上隅の x 座標。 |
| y | Single | 描画されたテキストの左上隅の y 座標。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush* null です。 -または- *s*無効である。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../../brush/)と[`Font`](../../font/)オブジェクト.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| s | String | 描画する文字列。 |
| font | Font | [`Font`](../../font/)文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/)描画されるテキストの色とテクスチャを決定します。 |
| point | PointF | [`PointF`](../../pointf/)描画されるテキストの左上隅を指定する構造体。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush* null です。 -または- *s*無効である。 |

### 例

この例では、Font および SolidBrush クラスを使用して、イメージ サーフェスに文字列を描画する方法を示します。この例では、新しい画像を作成し、Figure と GraphicsPath を使用して図形を描画します

```csharp
[C#]

//Image のインスタンスを作成します
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics クラスのインスタンスを作成して初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // グラフィック サーフェスをクリアします
    graphics.Clear(Color.Wheat);

    //Font のインスタンスを作成します
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //赤色の SolidBrush のインスタンスを作成します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //文字列を描画
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // エクスポート オプションを作成します。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // すべての変更を保存
    image.Save("C:\\temp\\output.gif", options);
}
```

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../../brush/)と[`Font`](../../font/)指定された書式設定属性を使用するオブジェクト[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| s | String | 描画する文字列。 |
| font | Font | [`Font`](../../font/)文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/)描画されるテキストの色とテクスチャを決定します。 |
| x | Single | 描画されたテキストの左上隅の x 座標。 |
| y | Single | 描画されたテキストの左上隅の y 座標。 |
| format | StringFormat | [`StringFormat`](../../stringformat/)描画されたテキストに適用される行間隔や配置などの書式設定属性を指定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush* null です。 -または- *s*無効である。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

指定した位置に指定した文字列を指定した文字列で描画します。[`Brush`](../../brush/)と[`Font`](../../font/)指定された書式設定属性を使用するオブジェクト[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| s | String | 描画する文字列。 |
| font | Font | [`Font`](../../font/)文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/)描画されるテキストの色とテクスチャを決定します。 |
| point | PointF | [`PointF`](../../pointf/)描画されるテキストの左上隅を指定する構造体。 |
| format | StringFormat | [`StringFormat`](../../stringformat/)描画されたテキストに適用される行間隔や配置などの書式設定属性を指定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush* null です。 -または- *s*無効である。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

指定されたテキスト文字列を、指定された長方形内に指定された色で描画します。[`Brush`](../../brush/)と[`Font`](../../font/)オブジェクト.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| s | String | 描画する文字列。 |
| font | Font | [`Font`](../../font/)文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/)描画されるテキストの色とテクスチャを決定します。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/)描画されるテキストの位置を指定する構造体。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush* null です。 -または- *s*無効である。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

指定されたテキスト文字列を、指定された長方形内に指定された色で描画します。[`Brush`](../../brush/)と[`Font`](../../font/)指定された書式設定属性を使用するオブジェクト[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| s | String | 描画する文字列。 |
| font | Font | [`Font`](../../font/)文字列のテキスト形式を定義します。 |
| brush | Brush | [`Brush`](../../brush/)描画されるテキストの色とテクスチャを決定します。 |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/)描画されるテキストの位置を指定する構造体。 |
| format | StringFormat | [`StringFormat`](../../stringformat/)描画されたテキストに適用される行間隔や配置などの書式設定属性を指定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush* null です。 -または- *s* null です。 -または- *brush*無効である。 |

### 関連項目

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)


