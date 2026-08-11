---
title: "列挙型 StringFormatFlags"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.StringFormatFlags 列挙型。テキスト文字列の表示およびレイアウト情報を指定します。"
type: docs
weight: 6180
url: /ja/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

テキスト文字列の表示およびレイアウト情報を指定します。

```csharp
[Flags]
public enum StringFormatFlags
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| DirectionRightToLeft | `1` | テキストは右から左へ表示されます。 |
| DirectionVertical | `2` | テキストは垂直方向に配置されます。 |
| FitBlackBox | `4` | 文字の一部が文字列のレイアウト矩形からはみ出すことが許可されています。デフォルトでは、はみ出しを防ぐために文字が再配置されます。 |
| DisplayFormatControl | `20` | 左から右へのマークなどの制御文字は、代表的なグリフで出力に表示されます。 |
| NoFontFallback | `400` | 要求されたフォントでサポートされていない文字に対する代替フォントへのフォールバックは無効です。欠落した文字は、通常は空白の四角形であるフォントの欠損グリフで表示されます。 |
| MeasureTrailingSpaces | `800` | 各行の末尾の空白を含めます。デフォルトでは、MeasureString メソッドが返す境界矩形は各行末尾の空白を除外します。このフラグを設定すると、測定時にその空白を含めます。 |
| NoWrap | `1000` | 矩形内で書式設定する際の行間のテキスト折り返しは無効になります。このフラグは、矩形の代わりに点が渡された場合、または指定された矩形の行長さがゼロの場合に暗黙的に適用されます。 |
| LineLimit | `2000` | 書式設定矩形には全行のみが配置されます。デフォルトでは、テキストの末尾まで、またはクリッピングの結果としてそれ以上の行が表示されなくなるまでレイアウトが続き、いずれか早い方が適用されます。デフォルト設定では、行の高さの整数倍でない書式設定矩形により最後の行が部分的に隠れることがあります。全行が確実に表示されるようにするには、この値を指定し、少なくとも1行分の高さと同等の書式設定矩形を提供するよう注意してください。 |
| NoClip | `4000` | グリフのはみ出し部分や、書式設定矩形の外に達する折り返しされていないテキストは表示が許可されます。デフォルトでは、書式設定矩形の外に出たすべてのテキストとグリフの部分はクリップされます。 |
| ExactAlignment | `8000` | 正確な配置、正しいパディング GDI+ |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


