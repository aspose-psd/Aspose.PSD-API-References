---
title: "فئة CmykColorHelper"
type: docs
weight: 640
url: /ar/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | ينشئ ألوان CMYK من قيم سيان، ماجنتا، أصفر وأسود 32-بت. |
| [get_c(cmyk)](#get_c_cmyk_2) | يحصل على قيمة المكوّن السيان. |
| [get_k(cmyk)](#get_k_cmyk_3) | يحصل على قيمة المكوّن الأسود. |
| [get_m(cmyk)](#get_m_cmyk_4) | يحصل على قيمة المكوّن الماجنتا. |
| [get_y(cmyk)](#get_y_cmyk_5) | يحصل على قيمة المكوّن الأصفر. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع الملفات التعريفية الافتراضية. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع الملفات التعريفية الافتراضية. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | يحوّل RGB إلى CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

ينشئ ألوان CMYK من قيم سيان، ماجنتا، أصفر وأسود 32-بت.

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
| int | لون CMYK معروض كقيمة عدد صحيح 32-بت. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

يحصل على قيمة المكوّن السيان.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | قيمة المكوّن السماوي. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

يحصل على قيمة المكوّن الأسود.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | قيمة المكوّن الأسود. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

يحصل على قيمة المكوّن الماجنتا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | قيمة المكوّن الأرجواني. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

يحصل على قيمة المكوّن الأصفر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk | int | لون CMYK معروض كقيمة عدد صحيح 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | قيمة المكوّن الأصفر. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ألوان ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ألوان ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان ARGB معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع الملفات التعريفية الافتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ألوان ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ألوان ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع الملفات التعريفية الافتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int | بكسلات CMYK معروضة كقيم أعداد صحيحة 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ألوان ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| cmyk_pixels | int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ألوان ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_pixels | int | ألوان ARGB معروضة كقيم أعداد صحيحة 32-بت. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

يحوّل RGB إلى CMYK.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| argb_pixels | int | ألوان RGB المعروضة كقيم صحيحة 32‑بت. |
| start_index | int | فهرس البداية للون RGB. |
| الطول | int | عدد بكسلات RGB التي سيتم تحويلها. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | ألوان CMYK المعروضة كمصفوفة بايت. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ألوان ARGB. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ألوان ARGB. |
| rgb_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ RGB. |
| cmyk_icc_stream | _io.BufferedRandom | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | ألوان CMYK معروضة كقيم أعداد صحيحة 32-بت. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixels | int | ألوان RGB المعروضة كقيم صحيحة 32‑بت. |
| start_index | int | فهرس البداية للون RGB. |
| الطول | int | عدد بكسلات RGB التي سيتم تحويلها. |
| rgb_icc_stream | _io.BufferedRandom | دفق ملف تعريف RGB. |
| cmyk_icc_stream | _io.BufferedRandom | دفق ملف تعريف CMYK. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | ألوان CMYK المعروضة كمصفوفة بايت. |


