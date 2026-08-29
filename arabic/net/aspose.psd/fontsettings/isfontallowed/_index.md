---
title: "FontSettings.IsFontAllowed"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة FontSettings. تحدد ما إذا كان الخط مسموحًا به لاسم الخط المحدد"
type: docs
weight: 90
url: /ar/net/aspose.psd/fontsettings/isfontallowed/
---
{{< psd/tize >}}
## FontSettings.IsFontAllowed method

يحدد ما إذا كان [is font allowed] [اسم الخط المحدد].

```csharp
public static bool IsFontAllowed(string fontName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | String | اسم الخط. |

### قيمة الإرجاع

`true` إذا [is font allowed] [the specified font name]؛ وإلا `false`.

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


