---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة FontSettings. يحدد قائمة استبدال الخطوط. إذا لم يكن الخط مسموحًا به فسيتم العثور على بديل. سيتم استخدام أول خط في القائمة أولاً. إذا كان مقيدًا أيضًا فسيتم اختيار الخط التالي من القائمة. إذا لم يكن للخط بدائل أو جميع البدائل غير مسموح بها فسيتم استخدام أول خط مسموح به من قائمة الخطوط المسموح بها. إذا لم توجد خطوط مسموح بها ومتاحة فستحاول المكتبة استخدام الخط الافتراضي للنظام حتى وإن لم يكن مسموحًا به."
type: docs
weight: 130
url: /ar/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

يضبط قائمة استبدال الخطوط. إذا لم يُسمح بالخط فسيتم العثور على بديل. سيُستخدم أول خط في القائمة أولاً. إذا كان مقيدًا أيضًا، فسيتم اختيار الخط التالي من القائمة. إذا لم يكن للخط بدائل أو لم تُسمح جميع البدائل فسيُستخدم أول خط مسموح من قائمة الخطوط المسموح بها. إذا لم تكن هناك خطوط مسموح بها ومتوفرة فستحاول المكتبة استخدام الخط الافتراضي للنظام حتى وإن لم يُسمح به.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontToReplace | String | الخط المراد استبداله. |
| fontNames | String[] | أسماء الخطوط البديلة بترتيب التشابه. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يجب أن يكون طول مصفوفة الخطوط ومصفوفة اختلافات الخطوط متساويين |

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


