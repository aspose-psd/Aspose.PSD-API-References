---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD for .NET API 参考
description: FontSettings 方法. 设置字体替换列表如果不允许使用字体则将找到替换字体 将首先使用列表中的第一个字体如果它也受到限制则将从列表中选择下一个字体 如果字体没有替换或不允许所有替换则将使用允许字体列表中的第一个允许字体 如果没有允许和可用的字体则库将尝试使用系统默认字体即使它是不允许的
type: docs
weight: 110
url: /zh/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

设置字体替换列表。如果不允许使用字体，则将找到替换字体。 将首先使用列表中的第一个字体。如果它也受到限制，则将从列表中选择下一个字体。 如果字体没有替换或不允许所有替换，则将使用允许字体列表中的第一个允许字体。 如果没有允许和可用的字体，则库将尝试使用系统默认字体，即使它是不允许的。

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontToReplace | String | 要替换的字体。 |
| fontNames | String[] | 替换字体名称按相似度排序。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 字体数组的长度和字体差异数组的长度必须相等 |

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


