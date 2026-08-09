---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD for .NET API 参考"
description: "FontSettings 方法。设置字体替换列表。如果字体不被允许，则会寻找替代字体。列表中的第一个字体将首先使用。如果它也被限制，则会选择列表中的下一个字体。如果字体没有替代或所有替代都不被允许，则会使用允许字体列表中的第一个允许的字体。如果没有允许且可用的字体，库将尝试使用系统默认字体，即使它不被允许。"
type: docs
weight: 130
url: /zh/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

设置字体替换列表。如果字体不被允许，则寻找替代字体。列表中的第一个字体将首先使用。如果它也被限制，则选择列表中的下一个字体。如果字体没有替代或所有替代均不被允许，则使用允许字体列表中的第一个允许的字体。如果没有允许且可用的字体，库将尝试使用系统默认字体，即使它不被允许。

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontToReplace | String | 要替换的字体。 |
| fontNames | String[] | 按相似度顺序排列的替代字体名称。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 字体数组和字体差异数组的长度必须相等。 |

## 示例

以下代码演示了使用编程方式限制字体的能力。

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

### 另请参阅

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


