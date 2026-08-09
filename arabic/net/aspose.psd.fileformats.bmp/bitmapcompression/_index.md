---
title: "التعداد BitmapCompression"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Bmp.BitmapCompression. يحدد طرق ضغط bitmap المختلفة."
type: docs
weight: 1320
url: /ar/net/aspose.psd.fileformats.bmp/bitmapcompression/
---
{{< psd/tize >}}
## BitmapCompression enumeration

يحدد طرق ضغط البت ماب المختلفة.

```csharp
public enum BitmapCompression : uint
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Rgb | `0` | بدون ضغط. |
| Rle8 | `1` | ضغط RLE 8-بت/بكسل. يمكن استخدامه فقط مع صور bitmap ذات 8-بت/بكسل. |
| Rle4 | `2` | ضغط RLE 4-بت/بكسل. يمكن استخدامه فقط مع صور bitmap ذات 4-بت/بكسل. |
| Bitfields | `3` | حقول RGB. يمكن استخدامها فقط مع صور نقطية 16 و 32‑بت/بكسل. |
| Jpeg | `4` | ضغط JPEG. الصورة النقطية تحتوي على صورة JPEG. |
| Png | `5` | ضغط PNG. الصورة النقطية تحتوي على صورة PNG. |
| AlphaBitfields | `6` | حقول RGBA. يمكن استخدامها فقط مع صور نقطية 16 و 32‑بت/بكسل. |
| Dxt1 | `827611204` | ضغط DXT1. الصورة النقطية تحتوي على نسيج. |

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Bmp](../../aspose.psd.fileformats.bmp/)
* assembly [Aspose.PSD](../../)


