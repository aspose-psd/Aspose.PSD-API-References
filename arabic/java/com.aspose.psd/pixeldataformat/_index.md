---
title: "PixelDataFormat"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تنسيق بيانات البكسل."
type: docs
weight: 80
url: /ar/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

تنسيق بيانات البكسل. هذا كائن غير قابل للتغيير.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن System.Object المحدد يساوي هذه الحالة. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | يحصل على لون BGR بعدد محدد من البتات لكل عينة. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | يحصل على لون BGRA بعدد محدد من البتات لكل عينة. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل. |
| [getCaption()](#getCaption--) | يحصل على تسمية تنسيق بيانات البكسل. |
| [getChannelBits()](#getChannelBits--) | يحصل على عدد البتات لكل قناة. |
| [getChannelsCount()](#getChannelsCount--) | يحصل على عدد القنوات. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | يحصل على لون CIE Lab بعدد محدد من البتات لكل عينة. |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | يحصل على  PixelDataFormat  المعرفة لـ 32 بت لكل بكسل مع 8 بت لكل من السيان، الماجنتا، الأصفر والأسود. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | يحصل على لون CMYK بعدد محدد من البتات لكل عينة. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | يحصل على لون CMYK بعدد محدد من البتات لكل عينة. |
| [getCmyk16()](#getCmyk16--) | يحصل على [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المعرفة لـ 64 بت لكل بكسل مع 16 بت لكل من السيان، الماجنتا، الأصفر والأسود. |
| [getCmyka()](#getCmyka--) | يحصل على acmyk. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | يحصل على لون CMYKA بعدد محدد من البتات لكل عينة. |
| [getCmyka16()](#getCmyka16--) | يحصل على acmyk. |
| [getGrayscale()](#getGrayscale--) | يحصل على  PixelDataFormat  المعرفة لـ 8 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في النطاق 0-255. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | يحصل على لون التدرج الرمادي بعدد محدد من البتات لكل عينة. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | يحصل على  PixelDataFormat  المعرفة لـ 16 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في النطاق 0-255 ومكوّن ألفا إضافي 8 بت. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | يحصل على لون GrayscaleAlpha بعدد محدد من البتات لكل عينة. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | يحصل على لون GrayscaleAlpha بعدد محدد من البتات لكل عينة. |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | يحصل على [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المعرفة لـ 32 بت لكل بكسل تمثل شدة التدرج الرمادي بصيغة النقطة العائمة. |
| [getPixelFormat()](#getPixelFormat--) | يحصل على تنسيق البكسل. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | يحصل على لون RGB بعدد محدد من البتات لكل عينة. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | يحصل على لون RGB بعدد محدد من البتات لكل عينة. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | يحصل على  PixelDataFormat  المعرفة لـ 16 بت لكل بكسل مع 5 بت لكل من الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | يحصل على  PixelDataFormat  المعرفة لـ 16 بت لكل بكسل مع 5 بت للأحمر، 6 بت للأخضر و5 بت للأزرق، ولا يتم تعريف ألفا. |
| [getRgb24Bpp()](#getRgb24Bpp--) | يحصل على  PixelDataFormat  المعرفة لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا. |
| [getRgb24BppPng()](#getRgb24BppPng--) | يحصل على  PixelDataFormat  المعرفة لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا. |
| [getRgb32Bpp()](#getRgb32Bpp--) | يحصل على  PixelDataFormat  المعرفة لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | يحصل على لون BGRA المفهرس بعدد محدد من البتات لكل عينة. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | يحصل على  PixelDataFormat  المعرفة للون المفهرس 1 بت لكل لون. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | يحصل على  PixelDataFormat  المعرفة للون المفهرس 2 بت لكل لون. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | يحصل على  PixelDataFormat  المعرفة للون المفهرس 4 بت لكل لون. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | يحصل على  PixelDataFormat  المعرفة للون المفهرس 8 بت لكل لون. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | يحصل على لون RGBA بعدد محدد من البتات لكل عينة. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | يحصل على لون RGBA بعدد محدد من البتات لكل عينة. |
| [getRgba32Bpp()](#getRgba32Bpp--) | يحصل على  PixelDataFormat  المعرفة لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق. |
| [getRgba64Bpp()](#getRgba64Bpp--) | يحصل على [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المحدد لـ 64 بت لكل بكسل مع 16 بت لكل من ألفا، الأحمر، الأخضر والأزرق. |
| [getYCbCr()](#getYCbCr--) | يحصل على  PixelDataFormat  المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من مكوّنات اللون اللومي، الفرق الأزرق والفرق الأحمر. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | يحصل على لون YCbCr بعدد محدد من البت لكل عينة. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | يحصل على لون YCbCr بعدد محدد من البت لكل عينة. |
| [getYcck()](#getYcck--) | يحصل على  PixelDataFormat  المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من مكوّنات اللون اللومي، الفرق الأزرق، الفرق الأحمر واللون الأسود. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | يحصل على لون YCCK بعدد محدد من البت لكل عينة. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا الكائن. |
| [isIndexed_internalized()](#isIndexed-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن مفهرسًا. |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | يعيد نتيجة المساواة لفئتين  PixelDataFormat  فئات. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | يعيد نتيجة عدم المساواة لفئتين  PixelDataFormat  فئات. |
| [toString()](#toString--) | يرجع  System.String  الذي يمثل هذه الحالة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن System.Object المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن System.Object للمقارنة مع هذا الكائن. |

**Returns:**
منطقية - true إذا كان الكائن System.Object المحدد مساويًا لهذا الكائن؛ وإلا false.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


يحصل على لون BGR بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


يحصل على لون BGRA بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد البتات لكل بكسل.

**Returns:**
int - عدد البت لكل بكسل.
### getCaption() {#getCaption--}
```
public String getCaption()
```


يحصل على تسمية تنسيق بيانات البكسل.

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


يحصل على عدد البتات لكل قناة.

**Returns:**
int[] - بت القناة.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


يحصل على عدد القنوات.

**Returns:**
int - عدد القنوات.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


يحصل على لون CIE Lab بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerL | int | عدد البت لكل قناة L. |
| bitsPerA | int | عدد البت لكل قناة A. |
| bitsPerB | int | عدد البت لكل قناة B. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CIE Lab color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


يحصل على  PixelDataFormat  المعرفة لـ 32 بت لكل بكسل مع 8 بت لكل من السيان، الماجنتا، الأصفر والأسود.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


يحصل على لون CMYK بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


يحصل على لون CMYK بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerCyanChannel | int | عدد البت لكل قناة سماوي. |
| bitsPerMagentaChannel | int | عدد البت لكل قناة أرجواني. |
| bitsPerYellowChannel | int | عدد البت لكل قناة أصفر. |
| bitsPerKeyChannel | int | عدد البتات لكل قناة المفتاح. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


يحصل على [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المعرفة لـ 64 بت لكل بكسل مع 16 بت لكل من السيان، الماجنتا، الأصفر والأسود.

القيمة: الـ [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المحدد لـ 64 بت لكل بكسل مع 16 بت لكل من السماوي، الأرجواني، الأصفر والأسود.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


يحصل على acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


يحصل على لون CMYKA بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerCyanChannel | int | عدد البت لكل قناة سماوي. |
| bitsPerMagentaChannel | int | عدد البت لكل قناة أرجواني. |
| bitsPerYellowChannel | int | عدد البت لكل قناة أصفر. |
| bitsPerKeyChannel | int | عدد البتات لكل قناة المفتاح. |
| bitsPerAlphaChannel | int | عدد البتات لكل قناة ألفا. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


يحصل على acmyk.

القيمة: الـ [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المحدد لـ 80 بت لكل بكسل مع 16 بت لكل من ألفا، السماوي، الأرجواني، الأصفر والأسود.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


يحصل على  PixelDataFormat  المعرفة لـ 8 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في النطاق 0-255.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


يحصل على لون التدرج الرمادي بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


يحصل على  PixelDataFormat  المعرفة لـ 16 بت لكل بكسل مع 8 بت تمثل شدة التدرج الرمادي في النطاق 0-255 ومكوّن ألفا إضافي 8 بت.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


يحصل على لون GrayscaleAlpha بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


يحصل على لون GrayscaleAlpha بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |
| alphaChannelBits | int | عدد البتات لكل عينة في قناة ألفا. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


يحصل على [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المعرفة لـ 32 بت لكل بكسل تمثل شدة التدرج الرمادي بصيغة النقطة العائمة.

القيمة: الـ [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المحدد لـ 32 بت لكل بكسل يمثل شدة التدرج الرمادي بصيغة النقطة العائمة

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


يحصل على تنسيق البكسل.

**Returns:**
int - تنسيق البكسل.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


يحصل على لون RGB بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


يحصل على لون RGB بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerRedChannel | int | عدد البتات لكل قناة الأحمر. |
| bitsPerGreenChannel | int | عدد البتات لكل قناة الأخضر. |
| bitsPerBlueChannel | int | عدد البتات لكل قناة الأزرق. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


يحصل على  PixelDataFormat  المعرفة لـ 16 بت لكل بكسل مع 5 بت لكل من الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


يحصل على  PixelDataFormat  المعرفة لـ 16 بت لكل بكسل مع 5 بت للأحمر، 6 بت للأخضر و5 بت للأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


يحصل على  PixelDataFormat  المعرفة لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


يحصل على  PixelDataFormat  المعرفة لـ 24 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق، ولا يتم تعريف ألفا.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


يحصل على  PixelDataFormat  المعرفة لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


يحصل على لون BGRA المفهرس بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


يحصل على الـ  PixelDataFormat  المحدد للون المفهرس ببت واحد لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


يحصل على الـ  PixelDataFormat  المحدد للون المفهرس ببتين لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


يحصل على الـ  PixelDataFormat  المحدد للون المفهرس بأربع بتات لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


يحصل على الـ  PixelDataFormat  المحدد للون المفهرس بثمانية بتات لكل لون. تم تصميم تخزين بيانات البكسل المفهرسة للسماح بتخزين البيانات واسترجاعها في كل مكان يُستخدم فيه لوحة الألوان. استخدمه بحذر، لأنه قد يتطلب تحويلًا من لوحة ألوان إلى أخرى أو من RGBA إلى نموذج اللون المفهرس.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


يحصل على لون RGBA بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


يحصل على لون RGBA بعدد محدد من البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerRedChannel | int | عدد البتات لكل قناة الأحمر. |
| bitsPerGreenChannel | int | عدد البتات لكل قناة الأخضر. |
| bitsPerBlueChannel | int | عدد البتات لكل قناة الأزرق. |
| bitsPerAlphaChannel | int | عدد البتات لكل قناة ألفا. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


يحصل على  PixelDataFormat  المعرفة لـ 32 بت لكل بكسل مع 8 بت لكل من ألفا، الأحمر، الأخضر والأزرق.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


يحصل على [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المحدد لـ 64 بت لكل بكسل مع 16 بت لكل من ألفا، الأحمر، الأخضر والأزرق.

القيمة: الـ [PixelDataFormat](../../com.aspose.psd/pixeldataformat) المحدد لـ 64 بت لكل بكسل مع 16 بت لكل من ألفا، الأحمر، الأخضر والأزرق.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


يحصل على  PixelDataFormat  المحدد لـ 24 بت لكل بكسل مع 8 بت لكل من مكوّنات اللون اللومي، الفرق الأزرق والفرق الأحمر.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


يحصل على لون YCbCr بعدد محدد من البت لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


يحصل على لون YCbCr بعدد محدد من البت لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerY | int | عدد البتات لكل قناة Y. |
| bitsPerCb | int | عدد البتات لكل قناة Cb. |
| bitsPerCr | int | عدد البتات لكل قناة Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


يحصل على  PixelDataFormat  المحدد لـ 32 بت لكل بكسل مع 8 بت لكل من مكوّنات اللون اللومي، الفرق الأزرق، الفرق الأحمر واللون الأسود.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


يحصل على لون YCCK بعدد محدد من البت لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bitsPerSample | int | عدد البت لكل عينة. |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة لهذا الكائن، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن مفهرسًا.

القيمة:  true  إذا كان هذا الكائن مفهرسًا؛ وإلا،  false .

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان هذا الكائن مفهرسًا.
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| caption | java.lang.String |  |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


يعيد نتيجة المساواة لفئتين  PixelDataFormat  فئات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | أول  PixelDataFormat  للمقارنة. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | ثاني  PixelDataFormat  للمقارنة. |

**Returns:**
منطقي - True إذا كان كل من  pixelFormat1  و  pixelFormat2  يحتويان على بيانات متساوية أو إذا كانت كلا المعاملين فارغين.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


يعيد نتيجة عدم المساواة لفئتين  PixelDataFormat  فئات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | أول  PixelDataFormat  للمقارنة. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | ثاني  PixelDataFormat  للمقارنة. |

**Returns:**
منطقي - True إذا كان كل من  pixelFormat1  و  pixelFormat2  يحتويان على بيانات غير متساوية أو إذا كان أحد المعاملين فارغًا.
### toString() {#toString--}
```
public String toString()
```


يرجع  System.String  الذي يمثل هذه الحالة.

**Returns:**
java.lang.String - سلسلة System.String تمثل هذه الحالة.
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

