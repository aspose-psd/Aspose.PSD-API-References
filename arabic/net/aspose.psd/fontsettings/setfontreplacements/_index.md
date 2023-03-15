---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD لمرجع .NET API
description: FontSettings طريقة. يضبط قائمة استبدال الخطوط. إذا كان الخط غير مسموح به فسيتم العثور على بديل . سيتم استخدام أول خط في القائمة أولاً. إذا تم تقييده أيضًا  فسيتم تحديد الخط التالي من القائمة . إذا لم يتم استبدال الخط أو لم يتم السماح لجميع البدائل  فسيتم استخدام الخط المسموح به أولاً من قائمة الخطوط المسموح بها. حاول استخدام الخط الافتراضي للنظام حتى لو لم يكن مسموحًا به.
type: docs
weight: 110
url: /ar/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

يضبط قائمة استبدال الخطوط. إذا كان الخط غير مسموح به فسيتم العثور على بديل . سيتم استخدام أول خط في القائمة أولاً. إذا تم تقييده أيضًا ، فسيتم تحديد الخط التالي من القائمة . إذا لم يتم استبدال الخط أو لم يتم السماح لجميع البدائل ، فسيتم استخدام الخط المسموح به أولاً من قائمة الخطوط المسموح بها. حاول استخدام الخط الافتراضي للنظام حتى لو لم يكن مسموحًا به.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontToReplace | String | الخط المراد استبداله. |
| fontNames | String[] | أسماء الخطوط البديلة بترتيب التشابه. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | يجب أن يتساوى طول صفيف الخط وصفيف اختلافات الخط |

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


