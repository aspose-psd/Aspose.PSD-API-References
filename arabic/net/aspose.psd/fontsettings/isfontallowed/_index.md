---
title: FontSettings.IsFontAllowed
second_title: Aspose.PSD لمرجع .NET API
description: FontSettings طريقة. تحديد ما إذا كان الخط مسموحًا به اسم الخط المحدد .
type: docs
weight: 80
url: /ar/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

تحديد ما إذا كان [الخط مسموحًا به] [اسم الخط المحدد] .

```csharp
public static bool IsFontAllowed(string fontName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontName | String | اسم الخط. |

### قيمة الإرجاع

`حقيقي` إذا [كان الخط مسموحًا به] [اسم الخط المحدد] ؛ خلاف ذلك،`خطأ شنيع` .

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


