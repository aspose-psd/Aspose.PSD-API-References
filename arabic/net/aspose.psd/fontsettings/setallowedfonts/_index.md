---
title: FontSettings.SetAllowedFonts
second_title: Aspose.PSD لمرجع .NET API
description: FontSettings طريقة. يقيد الخط باستخدام قائمة الخطوط. يرجى التحقق من أسماء الخطوط الحقيقية قبل قيود قم بتعيين قائمة الخطوط المسموح بها على Null لإزالة القيود
type: docs
weight: 100
url: /ar/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

يقيد الخط باستخدام قائمة الخطوط. يرجى التحقق من أسماء الخطوط الحقيقية قبل قيود قم بتعيين قائمة الخطوط المسموح بها على Null لإزالة القيود

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontList | String[] | قائمة الخطوط. |

### أمثلة

يوضح الكود التالي القدرة على تقييد الخطوط برمجيًا باستخدام.

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

### أنظر أيضا

* class [FontSettings](../)
* مساحة الاسم [Aspose.PSD](../../fontsettings/)
* المجسم [Aspose.PSD](../../../)


