---
title: FontSettings.IsFontAllowed
second_title: Aspose.PSD for .NET API 参考
description: FontSettings 方法. 判断是否是否允许使用字体指定的字体名称.
type: docs
weight: 80
url: /zh/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

判断是否[是否允许使用字体][指定的字体名称].

```csharp
public static bool IsFontAllowed(string fontName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 字体名称。 |

### 返回值

`真的` if [是否允许使用字体] [指定的字体名称]；否则，`错误的` .

### 例子

以下代码演示了以编程方式限制字体使用的能力。

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

### 也可以看看

* class [FontSettings](../)
* 命名空间 [Aspose.PSD](../../fontsettings/)
* 部件 [Aspose.PSD](../../../)


