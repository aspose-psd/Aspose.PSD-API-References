---
title: Class FontSettings
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FontSettings فصل. إعدادات خط العارض لتنسيقات PSD العامة.
type: docs
weight: 4290
url: /ar/net/aspose.psd/fontsettings/
---
## FontSettings class

إعدادات خط العارض لتنسيقات PSD العامة.

```csharp
public static class FontSettings
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | الحصول على الاسم الافتراضي للخط أو تعيينه. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | يمسح جميع استبدالات الخطوط |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | يحصل على اسم خط adobe حسب اسم عائلة الخط. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | يحصل على مجلدات الخطوط الافتراضية. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | يحصل على صفيف بدائل الخط بواسطة اسم الخط |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات حيث يبحث Aspose.Words عن خطوط TrueType . |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | الحصول على خط الاستبدال الأنسب . إذا لم يتم السماح بجميع البدائل ، فسيتم إرجاع الخط المسموح به والمتوفر أولاً. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | تحديد ما إذا كان [الخط مسموحًا به] [اسم الخط المحدد] . |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى النظام الافتراضي. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | يقيد الخط باستخدام قائمة الخطوط. يرجى التحقق من أسماء الخطوط الحقيقية قبل قيود قم بتعيين قائمة الخطوط المسموح بها على Null لإزالة القيود |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | يضبط قائمة استبدال الخطوط. إذا كان الخط غير مسموح به فسيتم العثور على بديل . سيتم استخدام أول خط في القائمة أولاً. إذا تم تقييده أيضًا ، فسيتم تحديد الخط التالي من القائمة . إذا لم يتم استبدال الخط أو لم يتم السماح لجميع البدائل ، فسيتم استخدام الخط المسموح به أولاً من قائمة الخطوط المسموح بها. حاول استخدام الخط الافتراضي للنظام حتى لو لم يكن مسموحًا به. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | هذا اختصار لـ[`SetFontsFolders`](./setfontsfolders/) لتعيين دليل خطوط واحد فقط. لم يتم إجراء عمليات تدقيق على مجلد الخطوط. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | يضبط المجلدات التي يتم تحميل خطوط TrueType منها ويمسح جميع الخطوط المحملة. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | يقوم بتحديث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. تضمن هذه الطريقة أن الخطوط من مجلد الخطوط التي تستخدم طريقة FontSettings.SetFontsFolder (FontSettings) أو بعد إعادة تعيين الخطوط باستخدام FontSettings.Reset () ستؤخذ في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة عند استدعاء FontSettings.SetFontsFolder (FontSettings) أو FontSettings.Reset () لصور PSD. بدون استدعاء هذه الطريقة ، لا يوجد ضمان بأنه سيتم تحديث الخطوط. |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


