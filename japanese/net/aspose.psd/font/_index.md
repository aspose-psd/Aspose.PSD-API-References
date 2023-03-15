---
title: Class Font
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Font クラス. フォント フェースサイズおよびスタイル属性を含むテキストの特定の形式を定義しますこのクラスは継承できません.
type: docs
weight: 4280
url: /ja/net/aspose.psd/font/
---
## Font class

フォント フェース、サイズ、およびスタイル属性を含む、テキストの特定の形式を定義します。このクラスは継承できません.

```csharp
public sealed class Font
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | 新しい`Font`指定された既存の`Font`と[`FontStyle`](../fontstyle/)列挙. |
| [Font](font/#constructor_1)(string, float) | 新しい`Font`指定サイズを使用。文字セットはDefault、グラフィックスユニットをPoint、フォント スタイルRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | 新しい`Font`指定されたサイズとスタイルを使用します。文字セットはDefault、グラフィックスユニットをPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | 新しい`Font`指定されたサイズと単位を使用します。文字セットはDefault、スタイルはに設定されていますRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | 新しい`Font`指定されたサイズ、スタイル、および単位を使用します。 |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | 新しい`Font`指定されたサイズ、スタイル、単位、および文字セットを使用します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | かどうかを示す値を取得します。`Font`太字. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | この文字セットを指定するバイト値を取得します`Font`uses. |
| [Italic](../../aspose.psd/font/italic/) { get; } | かどうかを示す値を取得します。`Font`斜体です。 |
| [Name](../../aspose.psd/font/name/) { get; } | この面の名前を取得します`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | この全角サイズを取得します`Font`で指定された単位で測定されます。[`Unit`](./unit/)プロパティ. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | かどうかを示す値を取得します。`Font`フォントを通る水平線を指定します。 |
| [Style](../../aspose.psd/font/style/) { get; } | このスタイル情報を取得します`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | かどうかを示す値を取得します。`Font`下線が引かれています. |
| [Unit](../../aspose.psd/font/unit/) { get; } | この測定単位を取得します`Font` . |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | これの正確なディープ コピーを作成します`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | 指定されたオブジェクトが`Font`これと同じプロパティ値を持っています`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | このハッシュコードを取得します`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | これの人間が読める文字列表現を返します`Font` . |

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

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


