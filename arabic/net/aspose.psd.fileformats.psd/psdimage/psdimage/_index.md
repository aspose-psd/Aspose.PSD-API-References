---
title: PsdImage.PsdImage
second_title: Aspose.PSD لمرجع .NET API
description: PsdImage البناء. يقوم بتهيئة مثيل جديد لملفPsdImage فئة من مسار محدد من صورة نقطية وليس صورة psd في المسار. يستخدم لتهيئة صورة psd بالمعلمات الافتراضية  وضع اللون  RGB  4 قنوات  8 بت لكل قناة  الضغط  Raw .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
## PsdImage(string) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../) فئة من مسار محدد من صورة نقطية (وليس صورة psd في المسار). يستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - RGB ، 4 قنوات ، 8 بت لكل قناة ، الضغط - Raw .

```csharp
public PsdImage(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل بيانات البكسل واللوحة منه والتهيئة به. |

### أنظر أيضا

* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../) فئة من مسار محدد من صورة نقطية (وليس صورة psd في المسار) مع معلمات المُنشئ.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل بيانات البكسل واللوحة منه والتهيئة به. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق بت PSD لكل قناة. |
| channels | Int16 | تحسب قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط الاستخدام. |

### أنظر أيضا

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../) فئة من مسار محدد من صورة نقطية (وليس صورة psd في الدفق). يستخدم لتهيئة صورة psd بالمعلمات الافتراضية - وضع اللون - RGB ، 4 قنوات ، 8 بت لكل قناة ، الضغط - Raw .

```csharp
public PsdImage(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل بيانات البكسل واللوحة منه والتهيئة معه. |

### أنظر أيضا

* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../) فئة من مسار محدد من صورة نقطية (وليس صورة psd في الدفق) مع معلمات المُنشئ.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل بيانات البكسل واللوحة منه والتهيئة معه. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق بت PSD لكل قناة. |
| channels | Int16 | تحسب قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط الاستخدام. |

### أنظر أيضا

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../)فئة من الصورة النقطية الموجودة (وليس صورة psd) مع وضع ألوان RGB مع 4 قنوات 8 بت / قناة وبدون ضغط.

```csharp
public PsdImage(RasterImage rasterImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة المراد تحميل بيانات البكسل واللوحة منها والتهيئة معها. |

### أنظر أيضا

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../) فئة من الصورة النقطية الموجودة (وليس صورة psd) مع معلمات المُنشئ.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة المراد تحميل بيانات البكسل واللوحة منها والتهيئة معها. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق بت PSD لكل قناة. |
| channels | Int16 | تحسب قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط الاستخدام. |

### أنظر أيضا

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../) فئة مع عرض وارتفاع محددين. تستخدم لتهيئة صورة psd فارغة.

```csharp
public PsdImage(int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة. |
| height | Int32 | ارتفاع الصورة. |

### أنظر أيضا

* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`PsdImage`](../) فئة مع عرض محدد ، ارتفاع ، لوحة ، وضع اللون ، عدد القنوات وقنوات طول البت ومعلمات وضع الضغط المحددة. تستخدم لتهيئة صورة psd فارغة.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة. |
| height | Int32 | ارتفاع الصورة. |
| colorPalette | IColorPalette | لوحة الألوان. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق بت PSD لكل قناة. |
| channels | Int16 | تحسب قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط الاستخدام. |

### أنظر أيضا

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)


