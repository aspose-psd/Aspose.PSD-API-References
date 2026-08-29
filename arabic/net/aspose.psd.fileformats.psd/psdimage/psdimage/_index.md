---
title: "PsdImage.PsdImage"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ PsdImage. يهيئ مثيلًا جديدًا من فئة PsdImage من المسار المحدد لصورة نقطية وليس صورة PSD في المسار. يُستخدم لتهيئة صورة PSD بالمعلمات الافتراضية  وضع اللون  rgb 4 قنوات 8 بت لكل قناة  الضغط  Raw"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd/psdimage/psdimage/
---
{{< psd/tize >}}
## PsdImage(string) {#constructor_6}

يهيئ مثيلًا جديدًا من الفئة [`PsdImage`](../) من المسار المحدد لصورة نقطية (ليس صورة PSD في المسار). يُستخدم لتهيئة صورة PSD بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw.

```csharp
public PsdImage(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل بيانات البكسل واللوحة منه والتهيئة به. |

### انظر أيضًا

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(string, ColorModes, short, short, int, CompressionMethod) {#constructor_7}

يهيئ مثيلًا جديدًا من الفئة [`PsdImage`](../) من المسار المحدد لصورة نقطية (ليس صورة PSD في المسار) باستخدام معلمات المنشئ.

```csharp
public PsdImage(string path, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل بيانات البكسل واللوحة منه والتهيئة به. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق البت في PSD لكل قناة. |
| channels | Int16 | عدد قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط المراد استخدامه. |

### انظر أيضًا

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream) {#constructor_4}

ينشئ مثيلًا جديدًا لفئة [`PsdImage`](../) من المسار المحدد من صورة نقطية (ليس صورة PSD في الدفق). يُستخدم لتهيئة صورة PSD بالمعلمات الافتراضية - وضع اللون - rgb، 4 قنوات، 8 بت لكل قناة، الضغط - Raw.

```csharp
public PsdImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل بيانات البكسل واللوحة اللونية منه والتهيئة به. |

### انظر أيضًا

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(Stream, ColorModes, short, short, int, CompressionMethod) {#constructor_5}

ينشئ مثيلًا جديدًا لفئة [`PsdImage`](../) من المسار المحدد من صورة نقطية (ليس صورة PSD في الدفق) باستخدام معلمات المُنشئ.

```csharp
public PsdImage(Stream stream, ColorModes colorMode, short channelBitDepth, short channels, 
    int psdVersion, CompressionMethod compression)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل بيانات البكسل واللوحة اللونية منه والتهيئة به. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق البت في PSD لكل قناة. |
| channels | Int16 | عدد قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط المراد استخدامه. |

### انظر أيضًا

* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage) {#constructor}

ينشئ مثيلًا جديدًا لفئة [`PsdImage`](../) من صورة نقطية موجودة (ليس صورة PSD) بوضع اللون RGB مع 4 قنوات 8 بت/قناة وبدون ضغط.

```csharp
public PsdImage(RasterImage rasterImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة لتحميل بيانات البكسل واللوحة اللونية منها والتهيئة بها. |

### انظر أيضًا

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(RasterImage, ColorModes, short, short, int, CompressionMethod) {#constructor_1}

ينشئ مثيلًا جديدًا لفئة [`PsdImage`](../) من صورة نقطية موجودة (ليس صورة PSD) باستخدام معلمات المُنشئ.

```csharp
public PsdImage(RasterImage rasterImage, ColorModes colorMode, short channelBitDepth, 
    short channels, int psdVersion, CompressionMethod compression)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة لتحميل بيانات البكسل واللوحة اللونية منها والتهيئة بها. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق البت في PSD لكل قناة. |
| channels | Int16 | عدد قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط المراد استخدامه. |

### انظر أيضًا

* class [RasterImage](../../../aspose.psd/rasterimage/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int) {#constructor_2}

ينشئ مثيلًا جديدًا لفئة [`PsdImage`](../) بالعرض والارتفاع المحددين. يُستخدم لتهيئة صورة PSD فارغة.

```csharp
public PsdImage(int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |

### انظر أيضًا

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## PsdImage(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) {#constructor_3}

ينشئ مثيلًا جديدًا لفئة [`PsdImage`](../) بالعرض والارتفاع واللوحة اللونية ووضع اللون وعدد القنوات وطول البت لكل قناة ومعلمات وضع الضغط المحددة. يُستخدم لتهيئة صورة PSD فارغة.

```csharp
public PsdImage(int width, int height, IColorPalette colorPalette, ColorModes colorMode, 
    short channelBitDepth, short channels, int psdVersion, CompressionMethod compression)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |
| colorPalette | IColorPalette | لوحة الألوان. |
| colorMode | ColorModes | وضع اللون. |
| channelBitDepth | Int16 | عمق البت في PSD لكل قناة. |
| channels | Int16 | عدد قنوات PSD. |
| psdVersion | Int32 | إصدار PSD. |
| compression | CompressionMethod | ضغط المراد استخدامه. |

### انظر أيضًا

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* enum [ColorModes](../../colormodes/)
* enum [CompressionMethod](../../compressionmethod/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


