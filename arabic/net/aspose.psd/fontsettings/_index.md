---
title: "فئة FontSettings"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.FontSettings. إعدادات الخط لمُعالج صيغ PSD المتجهة العامة"
type: docs
weight: 4760
url: /ar/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

إعدادات خط عارض صيغ المتجهات العامة لـ PSD.

```csharp
public static class FontSettings
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | يحصل أو يعيّن الاسم الافتراضي للخط. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font]. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | يمسح جميع استبدالات الخطوط |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | يحصل على اسم خط أدوبي بناءً على اسم عائلة الخط. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | يحصل على مجلدات الخطوط الافتراضية. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | يحصل على مصفوفة استبدالات الخط بناءً على اسم الخط |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Words عن خطوط TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | يحصل على الخط البديل الأنسب. إذا لم يُسمح بجميع الاستبدالات فسيتم إرجاع أول خط مسموح ومتوفر. إذا لم تكن هناك خطوط متوفرة فسيتم إرجاع الخط من الوسيط. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | يحدد ما إذا كان [is font allowed] [اسم الخط المحدد]. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | يزيل ملف ذاكرة التخزين المؤقت للخط. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى الإعداد الافتراضي للنظام. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | يقيد استخدام الخط بواسطة قائمة الخطوط. يرجى التحقق من أسماء الخطوط الفعلية قبل التقييد. اضبط قائمة الخطوط المسموح بها إلى Null لإزالة القيود. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | يضبط قائمة استبدال الخطوط. إذا لم يُسمح بالخط فسيتم العثور على بديل. سيُستخدم أول خط في القائمة أولاً. إذا كان مقيدًا أيضًا، فسيتم اختيار الخط التالي من القائمة. إذا لم يكن للخط بدائل أو لم تُسمح جميع البدائل فسيُستخدم أول خط مسموح من قائمة الخطوط المسموح بها. إذا لم تكن هناك خطوط مسموح بها ومتوفرة فستحاول المكتبة استخدام الخط الافتراضي للنظام حتى وإن لم يُسمح به. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | هذا اختصار إلى [`SetFontsFolders`](./setfontsfolders/) لتعيين دليل خط واحد فقط. لا يتم إجراء أي فحص على مجلد الخطوط. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | يضبط المجلدات التي تُحمَّل منها خطوط TrueType ويمسح جميع الخطوط المحملة. لا يتم إجراء أي فحص على مجلدات الخطوط. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | يقوم بتحديث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. يضمن هذه الطريقة أن الخطوط من المجلد fontsFolder باستخدام الطريقة FontSettings.SetFontsFolder(fontsFolder) أو بعد إعادة تعيين الخطوط باستخدام FontSettings.Reset() سيتم أخذها في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة يتم فيها استدعاء FontSettings.SetFontsFolder(fontsFolder) أو FontSettings.Reset() لصور PSD. بدون استدعاء هذه الطريقة لا يوجد ضمان بتحديث الخطوط. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


