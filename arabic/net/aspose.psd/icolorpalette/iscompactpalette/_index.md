---
title: IColorPalette.IsCompactPalette
second_title: Aspose.PSD لمرجع .NET API
description: IColorPalette ملكية. الحصول على قيمة تشير إلى ما إذا كان يتم استخدام لوح ألوان مضغوط.
type: docs
weight: 40
url: /ar/net/aspose.psd/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

الحصول على قيمة تشير إلى ما إذا كان يتم استخدام لوح ألوان مضغوط.

```csharp
public bool IsCompactPalette { get; }
```

### Property_Value

`حقيقي` إذا تم استخدام لوح مضغوط ؛ خلاف ذلك،`خطأ شنيع`.

### ملاحظات

تعني اللوحة المضغوطة أن الصورة ستحتوي فقط على إدخالات اللوحة المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر إحكاما وستشغل مساحة أقل ؛ وإلا فسيكون هناك 2 ^ مدخلات BitsPerPixel وستحتفظ الصورة بمساحة أكبر لجميع إدخالات اللوحة الممكنة. قد يؤدي تعيين هذه القيمة على القيمة "true" وتغيير إدخالات اللوحة إلى حدوث عقوبة في الأداء نظرًا لأن حركة البيانات قد تحدث ، لذا استخدمها بعناية.

### أنظر أيضا

* interface [IColorPalette](../)
* مساحة الاسم [Aspose.PSD](../../icolorpalette/)
* المجسم [Aspose.PSD](../../../)


