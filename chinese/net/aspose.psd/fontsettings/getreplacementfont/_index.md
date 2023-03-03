---
title: FontSettings.GetReplacementFont
second_title: Aspose.PSD for .NET API 参考
description: FontSettings 方法. 获取最合适的替换字体 如果不允许所有替换则将返回第一个允许和可用的字体 如果没有可用字体则将从参数 返回字体
type: docs
weight: 70
url: /zh/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

获取最合适的替换字体。 如果不允许所有替换，则将返回第一个允许和可用的字体。 如果没有可用字体，则将从参数 返回字体

```csharp
public static string GetReplacementFont(string fontName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 字体名称。 |

### 返回值

替换字体的名称

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


