---
title: "FontSettings.GetReplacementFont"
second_title: "Aspose.PSD for .NET API Reference"
description: "FontSettings メソッド。最も適切な置換フォントを取得します。すべての置換が許可されていない場合は、最初に許可され利用可能なフォントが返されます。利用可能なフォントがない場合は、引数で指定されたフォントが返されます。"
type: docs
weight: 80
url: /ja/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

最適な置換フォントを取得します。すべての置換が許可されていない場合は、最初に許可され利用可能なフォントが返されます。利用可能なフォントがない場合は、引数で指定されたフォントが返されます。

```csharp
public static string GetReplacementFont(string fontName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | 文字列 | フォントの名前。 |

### 戻り値

置換されたフォントの名前

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


