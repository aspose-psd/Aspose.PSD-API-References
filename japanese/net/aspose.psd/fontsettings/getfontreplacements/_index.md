---
title: "FontSettings.GetFontReplacements"
second_title: "Aspose.PSD for .NET API Reference"
description: "FontSettings メソッド。フォント名からフォント置換配列を取得します。"
type: docs
weight: 60
url: /ja/net/aspose.psd/fontsettings/getfontreplacements/
---
{{< psd/tize >}}
## FontSettings.GetFontReplacements method

フォント名でフォント置換配列を取得します

```csharp
public static string[] GetFontReplacements(string fontName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | 文字列 | フォントの名前。 |

### 戻り値

提供されたフォントの置換名の配列

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


