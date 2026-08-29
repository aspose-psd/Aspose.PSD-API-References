---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية IColorPalette. يحصل على قيمة تشير إلى ما إذا كانت اللوحة المدمجة مستخدمة"
type: docs
weight: 40
url: /ar/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

يحصل على قيمة تشير إلى ما إذا تم استخدام لوحة ألوان مدمجة.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` إذا تم استخدام لوحة ألوان مضغوطة؛ وإلا `false`.

## ملاحظات

تعني لوحة الألوان المضغوطة أن الصورة ستحتوي فقط على مدخلات لوحة الألوان المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر ضغطًا وتشغل مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel مدخلًا وستحجز الصورة مساحة أكبر لجميع مدخلات لوحة الألوان الممكنة. ضبط هذه القيمة على true وتغيير مدخلات لوحة الألوان قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث، لذا استخدمها بحذر.

### انظر أيضًا

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


