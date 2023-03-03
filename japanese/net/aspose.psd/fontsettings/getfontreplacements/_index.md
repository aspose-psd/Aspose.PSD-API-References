---
title: FontSettings.GetFontReplacements
second_title: Aspose.PSD for .NET API リファレンス
description: FontSettings 方法. フォント名 でフォント置換配列を取得します
type: docs
weight: 50
url: /ja/net/aspose.psd/fontsettings/getfontreplacements/
---
## FontSettings.GetFontReplacements method

フォント名 でフォント置換配列を取得します

```csharp
public static string[] GetFontReplacements(string fontName)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | フォントの名前。 |

### 戻り値

提供されたフォントの置換名の配列

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


