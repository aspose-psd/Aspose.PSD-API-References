---
title: "クラス StringFormat"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.StringFormat クラス。配置方向やタブ位置などのテキストレイアウト情報、エリプシス挿入や数字の国別置換、OpenType 機能などの表示操作をカプセル化します。このクラスは継承できません。"
type: docs
weight: 6170
url: /ja/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

テキストレイアウト情報（配置、向き、タブストップなど）や表示操作（省略記号の挿入や数字のローカライズ置換など）および OpenType 機能をカプセル化します。このクラスは継承できません。

```csharp
public sealed class StringFormat : DisposableObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | 新しい `StringFormat` オブジェクトを初期化します。 |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | 指定された既存の `StringFormat` オブジェクトから新しい `StringFormat` オブジェクトを初期化します。 |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | 指定された [`StringFormatFlags`](../stringformatflags/) 列挙体と語で新しい `StringFormat` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | 汎用的なデフォルト `StringFormat` オブジェクトを取得します。 |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | 汎用的な組版用 `StringFormat` オブジェクトを取得します。 |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | 垂直平面上のテキスト配置情報を取得または設定します。 |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | カスタム文字識別子を取得または設定します。 |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | ローカル数字が西洋数字に置き換えられる際に使用される言語を取得または設定します。 |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | 数字置換に使用される方法を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | テキスト行の開始位置と最初のタブ位置の間のスペース数を取得します。 |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | 書式情報を含む [`StringFormatFlags`](../stringformatflags/) 列挙体を取得または設定します。 |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | この `StringFormat` オブジェクトの [`HotkeyPrefix`](../hotkeyprefix/) オブジェクトを取得または設定します。 |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | 水平面上の行揃えを取得または設定します。 |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | [`PageUnit`](../graphics/pageunit/) プロパティで指定された単位で、タブ位置間の距離の配列を取得します。 |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | この `StringFormat` オブジェクトの [`StringTrimming`](../stringtrimming/) 列挙体を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | この `StringFormat` オブジェクトのディープクローンを作成します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | オブジェクトが等しいかどうかを確認します。 |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | 現在のオブジェクトのハッシュコードを取得します。 |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | この `StringFormat` オブジェクトのタブ位置を設定します。 |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | この `StringFormat` オブジェクトを人間が読みやすい文字列に変換します。 |

### 関連項目

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


