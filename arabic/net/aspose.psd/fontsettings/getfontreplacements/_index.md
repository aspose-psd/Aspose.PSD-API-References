---
title: "FontSettings.GetFontReplacements"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة FontSettings. تحصل على مصفوفة استبدالات الخط حسب اسم الخط"
type: docs
weight: 60
url: /ar/net/aspose.psd/fontsettings/getfontreplacements/
---
{{< psd/tize >}}
## FontSettings.GetFontReplacements method

يحصل على مصفوفة استبدالات الخط بناءً على اسم الخط

```csharp
public static string[] GetFontReplacements(string fontName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | اسم الخط. |

### قيمة الإرجاع

مصفوفة من أسماء الاستبدالات للخطوط المقدمة

## أمثلة

الكود التالي يوضح القدرة على تقييد الخطوط برمجياً باستخدام.

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

### انظر أيضًا

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


