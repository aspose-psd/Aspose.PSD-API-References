---
title: "ColorPaletteHelper"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "فئة مساعدة لتعديل لوحات الألوان."
type: docs
weight: 28
url: /ar/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

فئة مساعدة لتعديل لوحات الألوان.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [create4Bit()](#create4Bit--) | ينشئ لوحة ألوان 4 بت. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | ينشئ لوحة تدرج رمادي 4 بت. |
| [create8Bit()](#create8Bit--) | ينشئ لوحة ألوان 8 بت. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | ينشئ لوحة تدرج رمادي 8 بت. |
| [createMonochrome()](#createMonochrome--) | ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة ألوان للصورة. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | احصل على لوحة ألوان 256، مكوّنة من البتات العليا لقيم ألوان الصورة الأولية. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | احصل على لوحة ألوان 256 موحدة. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | يحدد ما إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


ينشئ لوحة ألوان 4 بت.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


ينشئ لوحة تدرج رمادي 4 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| minIsWhite | boolean | إذا تم تعيينه إلى  true  تبدأ لوحة الألوان باللون الأبيض، وإلا تبدأ باللون الأسود. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


ينشئ لوحة ألوان 8 بت.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


ينشئ لوحة تدرج رمادي 8 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| minIsWhite | boolean | إذا تم تعيينه إلى  true  تبدأ لوحة الألوان باللون الأبيض، وإلا تبدأ باللون الأسود. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة ألوان للصورة. في حال وجود لوحة ألوان، سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة النقطية. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود الصورة الوجهة. |
| entriesCount | int | عدد الإدخالات المطلوب. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة ألوان للصورة. في حال وجود لوحة ألوان، سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة النقطية. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود الصورة الوجهة. |
| entriesCount | int | عدد الإدخالات المطلوب. |
| useImagePalette | boolean | إذا تم الضبط، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متاحة |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة ألوان للصورة. في حال وجود لوحة ألوان، سيتم استخدامها بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة النقطية. |
| entriesCount | int | عدد الإدخالات المطلوب. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


احصل على لوحة ألوان 256، مكوّنة من البتات العليا لقيم ألوان الصورة الأولية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


احصل على لوحة ألوان 256 موحدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


يحدد ما إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |

**Returns:**
منطقي -  true  إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة؛ وإلا  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

