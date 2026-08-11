---
title: "RawColor クラス"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor クラス。Raw Color クラスは、任意のチャンネル数、任意のカラーモード、任意のビット深度で色を保存するのに役立ちます。内部クラスの中には RawColor をネイティブ形式に変換する際に問題があるものがありますので、API が CMYK カラーを提供する場合は、提供された形式を使用する方が信頼性が高いです。また、Raw Color が変換できるケースもあります。"
type: docs
weight: 1650
url: /ja/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class は、任意のチャンネル数、任意のカラーモード、任意のビット深度の色を保存するのに役立ちます。注意点として、内部クラスの中には RawColor をそのネイティブ形式に変換する際に問題が生じるものがあります。そのため、API が CMYK カラーを提供する場合は、提供された形式を使用する方が信頼性が高くなります。また、Raw Color が変換できるケースも存在する場合があります。

```csharp
public sealed class RawColor
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | `RawColor` クラスの新しいインスタンスを初期化します。 |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | 事前定義されたカラーモードを使用してピクセルデータ形式から `RawColor` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | 従うべきカラーのモードです。 |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | 色のコンポーネントを取得します。各コンポーネントは個別のチャンネルであり、一般的でないカラースキームを使用する場合は、各チャンネルを個別に扱う方が良いです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | 取得可能な場合、色を int として取得します。 |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | 取得可能な場合、色を long として取得します。 |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Raw Color のビット深度を取得します。例えば、各チャンネル/コンポーネントが 8 ビットの ARGB カラーの場合、ビット深度は 32 ビットです。各チャンネル/コンポーネントが 16 ビットのフル ARGB カラーの場合、ビット深度は 64 ビットになります。ビット深度は各チャンネルのビット深度の合計として蓄積されます。異なるチャンネルが異なるビット深度を持つことも可能です。 |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | カラーモードの名前を取得します。カラーモード名はチャンネル/コンポーネントの名前から構成されます。 |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | 現在のオブジェクトのハッシュコードを取得します。 |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | 可能な場合、int 引数からすべてのチャンネルにデータを設定します。 |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | 可能な場合、int 引数からすべてのチャンネルにデータを設定します。 |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | == 演算子を実装します。 |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | != 演算子を実装します。 |

## 例

次のコードは、廃止された Color 構造体の代わりに RawColor クラスのサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


