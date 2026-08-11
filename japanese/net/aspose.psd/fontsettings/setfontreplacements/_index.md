---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD for .NET API Reference"
description: "FontSettings メソッド。フォント置換リストを設定します。フォントが許可されていない場合は置換フォントが検索されます。リストの最初のフォントが最優先で使用されます。もしそれも制限されている場合は、リストの次のフォントが選択されます。フォントに置換がない、またはすべての置換フォントが許可されていない場合は、許可されたフォントリストから最初に許可されたフォントが使用されます。許可されたフォントも利用可能なフォントもない場合、ライブラリはシステム既定のフォントを使用しようとします（たとえ許可されていなくても）。"
type: docs
weight: 130
url: /ja/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

フォント置換リストを設定します。フォントが許可されていない場合は置換フォントが検索されます。リストの最初のフォントが最優先で使用されます。もしそれも制限されている場合は、リストの次のフォントが選択されます。フォントに置換がない、またはすべての置換が許可されていない場合は、許可されたフォントリストから最初の許可されたフォントが使用されます。許可され利用可能なフォントがない場合、ライブラリは許可されていなくてもシステム既定フォントの使用を試みます。

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontToReplace | 文字列 | 置換対象のフォントです。 |
| fontNames | String[] | 類似度の順に並んだ置換フォント名です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | Font 配列と Font Differences 配列の長さは同じでなければなりません。 |

## 例

以下のコードは、プログラムでフォントを制限する機能を示しています。

```csharp
[C#]

string srcFile = "fonts_com_updated.psd";
string output = "etalon_fonts_com_updated.psd.png";

try
{
    var fontList = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    FontSettings.SetAllowedFonts(fontList);

    var myriadReplacement = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    var calibriReplacement = new string[] { "Webdings", "Courier New", "Bookman Old Style" };
    var arialReplacement = new string[] { "Bookman Old Style", "Courier New", "Webdings" };
    var timesReplacement = new string[] { "Arial", "NotExistedFont", "Courier New" };

    FontSettings.SetFontReplacements("MyriadPro-Regular", myriadReplacement);
    FontSettings.SetFontReplacements("Calibri", calibriReplacement);
    FontSettings.SetFontReplacements("Arial", arialReplacement);
    FontSettings.SetFontReplacements("Times New Roman", timesReplacement);

    using (PsdImage image = (PsdImage)Image.Load(srcFile,
        new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
    {
        image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
finally
{
    FontSettings.SetAllowedFonts(null);
    FontSettings.ClearFontReplacements();
}
```

### 関連項目

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


