---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة FontSettings. يُزيل ملف ذاكرة التخزين المؤقت للخط"
type: docs
weight: 100
url: /ar/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

يزيل ملف ذاكرة التخزين المؤقت للخط.

```csharp
public static void RemoveFontCacheFile()
```

## أمثلة

الكود التالي يوضح طريقة إزالة الملف الذي يحتوي على ذاكرة التخزين المؤقت للخطوط المحملة.

```csharp
[C#]

string src = "SimpleText.psd";

FontSettings.RemoveFontCacheFile();

using (var psdImage = (PsdImage)Image.Load(src))
{
    foreach (var layer in psdImage.Layers)
    {
        if (layer is TextLayer textLayer)
        {
            textLayer.GetFonts();
        }
    }
}
```

### انظر أيضًا

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


