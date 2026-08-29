---
title: "Timeline.Save"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Timeline. تحفظ ملفات PsdImages وبيانات Timeline إلى موقع الملف المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ."
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

يحفظ بيانات PsdImage و Timeline إلى موقع الملف المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| خيارات | ImageOptionsBase | الخيارات. |

## أمثلة

الكود التالي يوضح دعم تصدير Timeline إلى صورة Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

يحفظ بيانات PsdImage و Timeline إلى الدفق المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق الإخراج. |
| خيارات | ImageOptionsBase | الخيارات. |

## أمثلة

الكود التالي يوضح دعم تصدير Timeline إلى صورة Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


