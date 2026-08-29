---
title: "FontSettings"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "إعدادات خطوط عارض صيغ المتجهات العامة للتصوير."
type: docs
weight: 47
url: /ar/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

إعدادات خطوط عارض صيغ المتجهات العامة للتصوير.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | يحصل على اسم خط adobe حسب اسم عائلة الخط. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | يحصل على اسم الخط الافتراضي. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | يحصل على مجلدات الخطوط الافتراضية. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | يحصل على مصفوفة استبدالات الخط حسب اسم الخط |
| [getFontsFolders()](#getFontsFolders--) | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Imaging عن خطوط TrueType. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | يحصل على الخط البديل الأنسب. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | يحدد ما إذا كان [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | يزيل ملف ذاكرة التخزين المؤقت للخط. |
| [reset()](#reset--) | يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى الإعداد الافتراضي للنظام. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | يقيد استخدام الخط بقائمة الخطوط. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | يعيّن اسم الخط الافتراضي. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | يعيّن قائمة استبدال الخط. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | تجاوز قائمة مجلد الخطوط للمجلد. |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | تجاوز قائمة مجلد الخطوط للمجلدات. |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | يعيّن المجلدات التي يتم تحميل خطوط TrueType منها ويمسح جميع الخطوط المحمّلة. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | يحدّث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


يحصل على اسم خط adobe حسب اسم عائلة الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontFamilyName | java.lang.String | اسم عائلة الخط. |

**Returns:**
java.lang.String - اسم خط Adobe حسب اسم عائلة الخط.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


يحصل على اسم الخط الافتراضي.

**Returns:**
java.lang.String - اسم الخط الافتراضي
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


يحصل على مجلدات الخطوط الافتراضية.

**Returns:**
java.lang.String[] - يُعيد مجلد النظام
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


يحصل على مصفوفة استبدالات الخط حسب اسم الخط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط. |

**Returns:**
java.lang.String[] - مصفوفة بأسماء الاستبدالات للخطوط المقدمة
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


يحصل على نسخة من المصفوفة التي تحتوي على قائمة المجلدات التي يبحث فيها Aspose.Imaging عن خطوط TrueType.

القيمة المعادة هي نسخة من البيانات التي يستخدمها Aspose.Imaging. إذا قمت بتغيير العناصر في المصفوفة المعادة، فلن يكون لها أي تأثير على عرض المستند. لتحديد مواقع خطوط جديدة استخدم طريقة  setFontsFolders .

**Returns:**
java.lang.String[] - نسخة من مواقع الخط الحالية.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font].

القيمة:  true  إذا كان [get alternative font]; وإلا،  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


يحصل على الخط البديل الأنسب. إذا لم يُسمح بجميع الاستبدالات فسيتم إرجاع أول خط مسموح ومتوافر. إذا لم تتوفر أي خطوط، فسيتم إرجاع الخط المقدم كمعامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط. |

**Returns:**
java.lang.String - اسم الخط المستبدل
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


يحدد ما إذا كان [is font allowed] [the specified font name].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط. |

**Returns:**
boolean -  true  إذا كان [is font allowed] [the specified font name]; وإلا،  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


يزيل ملف ذاكرة التخزين المؤقت للخط.

### reset() {#reset--}
```
public static void reset()
```


يعيد تعيين مجلد الخطوط واسم الخط الافتراضي إلى الإعداد الافتراضي للنظام.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


يقيد الخط باستخدام قائمة الخطوط. يرجى التحقق من أسماء الخطوط الفعلية قبل القيد. اضبط قائمة الخطوط المسموح بها إلى Null لإزالة القيود

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontList | java.lang.String[] | قائمة الخطوط. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


يعيّن اسم الخط الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | الاسم الافتراضي للخط. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


يضبط قائمة استبدال الخطوط. إذا لم يكن الخط مسموحًا به فسيتم العثور على بديل. سيتم استخدام أول خط في القائمة أولاً. إذا تم تقييده أيضًا، فسيتم اختيار الخط التالي من القائمة. إذا لم يكن للخط بدائل أو كانت جميع البدائل غير مسموح بها، فسيتم استخدام أول خط مسموح به من قائمة الخطوط المسموح بها. إذا لم توجد خطوط مسموح بها ومتاحة، فستحاول المكتبة استخدام الخط الافتراضي للنظام حتى وإن لم يكن مسموحًا به.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontToReplace | java.lang.String | الخط المراد استبداله. |
| fontNames | java.lang.String[] | أسماء الخطوط البديلة بترتيب التشابه. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


تجاوز قائمة مجلد الخطوط للمجلد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folder | java.lang.String | مجلد يحتوي على خطوط TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


تجاوز قائمة مجلد الخطوط للمجلدات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folders | java.lang.String[] | مصفوفة من المجلدات |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


يضبط المجلدات التي يتم تحميل خطوط TrueType منها ويُمسح جميع الخطوط المحملة. لا يتم إجراء أي فحوصات على مجلدات الخطوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folders | java.lang.String[] | مجلدات الخطوط. |
| recursive | boolean | إذا تم ضبطه على  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [get alternative font].

القيمة:  true  إذا كان [get alternative font]; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


يقوم بتحديث ذاكرة التخزين المؤقت للخطوط لملفات PSD التي تحتوي على طبقات نصية. تضمن هذه الطريقة أن الخطوط من المجلد fontsFolder باستخدام الطريقة FontSettings.setFontsFolder(fontsFolder) أو بعد إعادة ضبط الخطوط باستخدام FontSettings.reset() سيتم أخذها في الاعتبار عند معالجة ملفات PSD. يرجى استخدام هذه الطريقة في كل مرة يتم فيها استدعاء FontSettings.setFontsFolder(fontsFolder) أو FontSettings.reset() لصور PSD. بدون استدعاء هذه الطريقة لا يوجد ضمان بأن الخطوط سيتم تحديثها.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

