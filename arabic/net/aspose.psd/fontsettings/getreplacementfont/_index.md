---
title: "FontSettings.GetReplacementFont"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة FontSettings. تحصل على الخط البديل الأنسب. إذا لم يُسمح بجميع الاستبدالات فسيتم إرجاع أول خط مسموح ومتوفر. إذا لم تتوفر أي خطوط فسيتم إرجاع الخط الممرّر كمعامل."
type: docs
weight: 80
url: /ar/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

يحصل على الخط البديل الأنسب. إذا لم يُسمح بجميع الاستبدالات فسيتم إرجاع أول خط مسموح ومتوفر. إذا لم تكن هناك خطوط متوفرة فسيتم إرجاع الخط من الوسيط.

```csharp
public static string GetReplacementFont(string fontName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | اسم الخط. |

### قيمة الإرجاع

اسم الخط المستبدل

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


