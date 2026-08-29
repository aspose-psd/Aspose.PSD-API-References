---
title: "クラス Font"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Font クラス。フォントのフェイスサイズやスタイル属性を含むテキストの特定の形式を定義します。このクラスは継承できません。"
type: docs
weight: 4750
url: /ja/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

フォントの種類、サイズ、スタイル属性を含むテキストの特定の形式を定義します。このクラスは継承できません。

```csharp
public sealed class Font
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | 指定された既存の `Font` と [`FontStyle`](../fontstyle/) 列挙体を使用する新しい `Font` を初期化します。 |
| [Font](font/#constructor_1)(string, float) | 指定されたサイズを使用して新しい `Font` を初期化します。文字セットは Default に、グラフィック単位は Point に、フォントスタイルは Regular に設定されます。 |
| [Font](font/#constructor_2)(string, float, FontStyle) | 指定されたサイズとスタイルを使用して新しい `Font` を初期化します。文字セットは Default に、グラフィック単位は Point に設定されます。 |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | 指定されたサイズと単位を使用して新しい `Font` を初期化します。文字セットは Default に、スタイルは Regular に設定されます。 |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | 指定されたサイズ、スタイル、単位を使用して新しい `Font` を初期化します。 |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | 指定されたサイズ、スタイル、単位、文字セットを使用して新しい `Font` を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | `Font` が太字かどうかを示す値を取得します。 |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | この `Font` が使用する文字セットを指定するバイト値を取得します。 |
| [Italic](../../aspose.psd/font/italic/) { get; } | `Font` がイタリックかどうかを示す値を取得します。 |
| [Name](../../aspose.psd/font/name/) { get; } | この `Font` のフェイス名を取得します。 |
| [Size](../../aspose.psd/font/size/) { get; } | `Font` の em サイズを、[`Unit`](./unit/) プロパティで指定された単位で測定した値を取得します。 |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | この `Font` がフォントに水平線を指定しているかどうかを示す値を取得します。 |
| [Style](../../aspose.psd/font/style/) { get; } | この `Font` のスタイル情報を取得します。 |
| [Underline](../../aspose.psd/font/underline/) { get; } | この `Font` が下線付きかどうかを示す値を取得します。 |
| [Unit](../../aspose.psd/font/unit/) { get; } | この `Font` の測定単位を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | この `Font` の正確なディープコピーを作成します。 |
| override [Equals](../../aspose.psd/font/equals/)(object) | 指定されたオブジェクトが `Font` であり、この `Font` と同じプロパティ値を持つかどうかを示します。 |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | この `Font` のハッシュコードを取得します。 |
| override [ToString](../../aspose.psd/font/tostring/)() | この `Font` の人間が読みやすい文字列表現を返します。 |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


