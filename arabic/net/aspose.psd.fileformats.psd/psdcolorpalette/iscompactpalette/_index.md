---
title: PsdColorPalette.IsCompactPalette
second_title: Aspose.PSD لمرجع .NET API
description: PsdColorPalette ملكية. يحصل على قيمة تشير إلى ما إذا كان سيتم ضغط لوح الألوان .
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

يحصل على قيمة تشير إلى ما إذا كان سيتم ضغط لوح الألوان .

```csharp
public bool IsCompactPalette { get; }
```

### Property_Value

`حقيقي` إذا ضغطت لوح الألوان ؛ خلاف ذلك،`خطأ شنيع`.

### ملاحظات

تعني اللوحة المضغوطة أن الصورة ستحتوي فقط على إدخالات اللوحة المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر إحكاما وتشغل مساحة أقل ؛ وإلا فسيكون هناك 2 ^ مدخلات BitsPerPixel وستحتفظ الصورة بمساحة أكبر لجميع إدخالات اللوحة الممكنة . قد يؤدي تعيين هذه القيمة إلى القيمة "true" وتغيير إدخالات اللوحة إلى حدوث عقوبة في الأداء نظرًا لأن حركة البيانات قد تحدث ، لذا استخدمها بعناية.

### أنظر أيضا

* class [PsdColorPalette](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* المجسم [Aspose.PSD](../../../)


