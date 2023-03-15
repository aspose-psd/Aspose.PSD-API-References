---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD for .NET API リファレンス
description: FontSettings 方法. フォント置換リストを設定しますフォントが許可されていない場合は代替が検出されます リストの最初の 1 つのフォントが最初に使用されますそれも制限されている場合はリストから次のフォントが選択されます. フォントに置換がないかすべての置換が許可されていない場合は許可されたフォントリストから最初に許可されたフォントが使用されます. 許可された使用可能なフォントがない場合ライブラリは許可されていない場合でもシステムのデフォルト フォントを使用してみてください
type: docs
weight: 110
url: /ja/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

フォント置換リストを設定します。フォントが許可されていない場合は、代替が検出されます。 リストの最初の 1 つのフォントが最初に使用されます。それも制限されている場合は、リストから次のフォントが選択されます. フォントに置換がないか、すべての置換が許可されていない場合は、許可されたフォントリストから最初に許可されたフォントが使用されます. 許可された使用可能なフォントがない場合、ライブラリは許可されていない場合でも、システムのデフォルト フォントを使用してみてください。

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontToReplace | String | 置き換えるフォント。 |
| fontNames | String[] | 類似した順に置換フォント名。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | フォント配列とフォント差分配列の長さは等しくなければなりません |

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


