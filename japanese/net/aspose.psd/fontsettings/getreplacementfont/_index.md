---
title: FontSettings.GetReplacementFont
second_title: Aspose.PSD for .NET API リファレンス
description: FontSettings 方法. 最適な代替フォントを取得します すべての置換が許可されていない場合は最初に許可された使用可能なフォントが返されます 使用可能なフォントがない場合は引数からフォントが返されます
type: docs
weight: 70
url: /ja/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

最適な代替フォントを取得します。 すべての置換が許可されていない場合は、最初に許可された使用可能なフォントが返されます。 使用可能なフォントがない場合は、引数からフォントが返されます

```csharp
public static string GetReplacementFont(string fontName)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | フォントの名前。 |

### 戻り値

置き換えられたフォントの名前

### 例

次のコードは、 を使用してプログラムでフォントを制限する機能を示しています。

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

    using (PsdImage image = (PsdImage)Image.Load(srcFile))
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
* 名前空間 [Aspose.PSD](../../fontsettings/)
* 組み立て [Aspose.PSD](../../../)


