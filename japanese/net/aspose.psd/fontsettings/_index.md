---
title: "クラス FontSettings"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FontSettings クラス。一般的な PSD ベクタ形式レンダラのフォント設定"
type: docs
weight: 4760
url: /ja/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

一般的な PSD ベクターフォーマットレンダラのフォント設定。

```csharp
public static class FontSettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | フォントのデフォルト名を取得または設定します。 |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | 代替フォントを取得するかどうかを示す値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | すべてのフォント置換をクリアします |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | フォントファミリ名から Adobe フォント名を取得します。 |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | デフォルトのフォントフォルダーを取得します。 |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | フォント名でフォント置換配列を取得します |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Aspose.Words が TrueType フォントを検索するフォルダーのリストを含む配列のコピーを取得します。 |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | 最適な置換フォントを取得します。すべての置換が許可されていない場合は、最初に許可され利用可能なフォントが返されます。利用可能なフォントがない場合は、引数で指定されたフォントが返されます。 |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | 指定されたフォント名が許可されているかどうかを判定します。 |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | フォントキャッシュファイルを削除します。 |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | フォントフォルダーとデフォルトフォント名をシステム既定にリセットします。 |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | フォントをフォントリストで制限します。制限前に実際のフォント名を確認してください。許可されたフォントリストを Null に設定すると制限が解除されます。 |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | フォント置換リストを設定します。フォントが許可されていない場合は置換フォントが検索されます。リストの最初のフォントが最優先で使用されます。もしそれも制限されている場合は、リストの次のフォントが選択されます。フォントに置換がない、またはすべての置換が許可されていない場合は、許可されたフォントリストから最初の許可されたフォントが使用されます。許可され利用可能なフォントがない場合、ライブラリは許可されていなくてもシステム既定フォントの使用を試みます。 |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | これは、1つのフォントディレクトリのみを設定するための [`SetFontsFolders`](./setfontsfolders/) へのショートカットです。フォントフォルダーに対するチェックは行われません。 |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | TrueType フォントが読み込まれるフォルダーを設定し、すべての読み込まれたフォントをクリアします。フォントフォルダーに対するチェックは行われません。 |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | テキストレイヤーを含む PSD ファイルのフォントキャッシュを更新します。このメソッドは、FontSettings.SetFontsFolder(fontsFolder) メソッドでフォルダー fontsFolder からフォントを使用する場合や、FontSettings.Reset() でフォントをリセットした後に、PSD ファイルの処理時にそれらのフォントが考慮されることを保証します。PSD 画像に対して FontSettings.SetFontsFolder(fontsFolder) または FontSettings.Reset() が呼び出されるたびにこのメソッドを使用してください。このメソッドを呼び出さない場合、フォントが更新される保証はありません。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


