---
title: FontSettings.IsFontAllowed
second_title: Aspose.PSD for .NET API リファレンス
description: FontSettings 方法. フォントが許可されている 指定されたフォント名 かどうかを決定します
type: docs
weight: 80
url: /ja/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

[フォントが許可されている] [指定されたフォント名] かどうかを決定します。

```csharp
public static bool IsFontAllowed(string fontName)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | フォントの名前。 |

### 戻り値

`真実` if [フォントが許可されている] [指定されたフォント名];さもないと、`間違い` .

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


