---
title: Class StringFormat
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.StringFormat クラス. テキスト レイアウト情報 配置向きタブ ストップなど表示操作 省略記号の挿入や各国の数字の置換などおよび OpenType 機能をカプセル化しますこのクラスは継承できません.
type: docs
weight: 5670
url: /ja/net/aspose.psd/stringformat/
---
## StringFormat class

テキスト レイアウト情報 (配置、向き、タブ ストップなど)、表示操作 (省略記号の挿入や各国の数字の置換など)、および OpenType 機能をカプセル化します。このクラスは継承できません.

```csharp
public sealed class StringFormat : DisposableObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | 新しい`StringFormat`object. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | 新しい`StringFormat`指定された既存のオブジェクト`StringFormat`object. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | 新しい`StringFormat`指定されたオブジェクト[`StringFormatFlags`](../stringformatflags/)列挙と言語. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | 汎用デフォルトを取得します`StringFormat`object. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | 一般的なタイポグラフィを取得します`StringFormat`object. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | 垂直面のテキスト配置情報を取得または設定します. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | ローカルの数字が西洋の数字に置き換えられるときに使用される言語を取得または設定します. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | 数字置換に使用する方法を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | テキスト行の先頭と最初のタブ ストップの間のスペース数を取得します。 |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | を取得または設定します[`StringFormatFlags`](../stringformatflags/)フォーマット情報を含む列挙. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | を取得または設定します[`HotkeyPrefix`](../hotkeyprefix/)このオブジェクト`StringFormat`object. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | 水平面上の行の配置を取得または設定します。 |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | で指定された単位でタブ ストップ間の距離の配列を取得します。[`PageUnit`](../graphics/pageunit/)プロパティ. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | を取得または設定します[`StringTrimming`](../stringtrimming/)この列挙`StringFormat`object. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | これのディープ クローンを作成します`StringFormat`object. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | これにタブストップを設定します`StringFormat`object. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | これを変換`StringFormat`人間が読める文字列へのオブジェクト. |

### 関連項目

* class [DisposableObject](../disposableobject/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


