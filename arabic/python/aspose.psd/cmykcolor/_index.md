---
title: "فئة CmykColor"
type: docs
weight: 630
url: /ar/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | يُنشئ نسخة جديدة من فئة CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| c | byte | r | يحصل على قيمة المكوّن السماوي لهذا الهيكل [Color](/psd/python-net/aspose.psd/color/). |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | يحصل على الفارغ. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه البنية [Color](/psd/python-net/aspose.psd/color/) غير مبدأة. |
| k | byte | r | يحصل على قيمة المكوّن الأسود لهذا الهيكل [Color](/psd/python-net/aspose.psd/color/). |
| m | byte | r | يحصل على قيمة المكوّن الأرجواني لهذا الهيكل [Color](/psd/python-net/aspose.psd/color/). |
| y | byte | r | يحصل على قيمة المكوّن الأصفر لهذا الهيكل [Color](/psd/python-net/aspose.psd/color/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | ينشئ هيكلًا من نوع [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) من قيم 32-بت للسماوي، الأرجواني، الأصفر والأسود.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | التحويل من CMYKColor إلى لون ARGB 32-بت باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | التحويل من لون ARGB 32-بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | التحويل من لون ARGB 32-بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) الأكثر فاعلية. |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية. |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) الأكثر فاعلية. |
| [to_value()](#to_value__11) | القيمة إلى. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

يُنشئ نسخة جديدة من فئة CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

ينشئ هيكلًا من نوع [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) من قيم 32-بت للسماوي، الأرجواني، الأصفر والأسود.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| سماوي | int | المكوّن السماوي. القيم الصالحة هي من 0 إلى 255. |
| أرجواني | int | المكوّن الأرجواني. القيم الصالحة هي من 0 إلى 255. |
| أصفر | int | المكوّن الأصفر. القيم الصالحة هي من 0 إلى 255. |
| أسود | int | المكوّن الأسود. القيم الصالحة هي من 0 إلى 255. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | الـ [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

التحويل من CMYKColor إلى لون ARGB 32-بت باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | بكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | المصفوفة الخاصة بلون ARGB 32-بت. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

التحويل من لون ARGB 32-بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | الـ <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

التحويل من لون ARGB 32-بت إلى CMYKColor.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_pixels | int | بكسلات بتنسيق ARGB 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | الـ <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | المصفوفة الخاصة بألوان ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | بكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | المصفوفة الخاصة بألوان ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | الـ [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | الـ [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية.<br/>            هذه الطريقة مهجورة. يرجى استخدام [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | بكسلات من نوع CMYKColor بتنسيق CMYK. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | الـ [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من CMYKColor إلى Color باستخدام تحويل icc.<br/>            هذه الطريقة مهجورة. يرجى استخدام Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) الأكثر فاعلية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | بكسلات من نوع CMYKColor بتنسيق CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف icc rgb. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | الـ [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

القيمة إلى.

**Returns**

| النوع | الوصف |
| :- | :- |
| long | العدد الصحيح. |


