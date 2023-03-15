---
title: Class FontSettings
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FontSettings クラス. 一般的な PSD ベクター フォーマットのレンダラー フォント設定.
type: docs
weight: 4290
url: /ja/net/aspose.psd/fontsettings/
---
## FontSettings class

一般的な PSD ベクター フォーマットのレンダラー フォント設定.

```csharp
public static class FontSettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | フォントのデフォルト名を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | すべてのフォントをクリアします replacements |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | フォント ファミリ名から Adobe フォント名を取得します。 |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | 既定のフォント フォルダーを取得します。 |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | フォント名 でフォント置換配列を取得します |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Aspose.Words が TrueType フォントを探すフォルダーのリストを含む配列のコピーを取得します。 |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | 最適な代替フォントを取得します。 すべての置換が許可されていない場合は、最初に許可された使用可能なフォントが返されます。 使用可能なフォントがない場合は、引数からフォントが返されます |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | [フォントが許可されている] [指定されたフォント名] かどうかを決定します。 |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | フォント フォルダとデフォルトのフォント名をシステムのデフォルトにリセットします。 |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | フォント一覧で使用するフォントを制限します。 Restriction の前に実際のフォント名を確認してください 許可されたフォント リストを Null に設定して、restrictions を削除します |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | フォント置換リストを設定します。フォントが許可されていない場合は、代替が検出されます。 リストの最初の 1 つのフォントが最初に使用されます。それも制限されている場合は、リストから次のフォントが選択されます. フォントに置換がないか、すべての置換が許可されていない場合は、許可されたフォントリストから最初に許可されたフォントが使用されます. 許可された使用可能なフォントがない場合、ライブラリは許可されていない場合でも、システムのデフォルト フォントを使用してみてください。 |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | へのショートカットです[`SetFontsFolders`](./setfontsfolders/) つのフォント ディレクトリのみを設定する場合. フォント フォルダに対して実行されるチェックはありません. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | TrueType フォントが読み込まれるフォルダを設定し、読み込まれたすべてのフォントをクリアします. フォント フォルダに対して実行されるチェックはありません. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | テキスト レイヤーを含む PSD ファイルのフォント キャッシュを更新します。このメソッドは、 メソッド FontSettings.SetFontsFolder(fontsFolder) を使用してフォルダー fontsFolder からのフォント、または FontSettings.Reset() を使用してフォントをリセットした後のフォントが、PSD ファイルの処理時に考慮されることを保証します。 PSD 画像に対して FontSettings.SetFontsFolder(fontsFolder) または FontSettings.Reset() を呼び出すたびに、このメソッドを使用してください。このメソッドを呼び出さないと、フォントが更新される保証はありません。 |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


