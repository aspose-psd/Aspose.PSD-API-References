---
title: FontSettings.SetAllowedFonts
second_title: Aspose.PSD for .NET API 参考
description: FontSettings 方法. 限制字体列表使用的字体请在 restriction 之前检查真实字体名称 将允许的字体列表设置为 Null 以删除 restrictions
type: docs
weight: 100
url: /zh/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

限制字体列表使用的字体。请在 restriction 之前检查真实字体名称 将允许的字体列表设置为 Null 以删除 restrictions

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontList | String[] | 字体列表。 |

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


