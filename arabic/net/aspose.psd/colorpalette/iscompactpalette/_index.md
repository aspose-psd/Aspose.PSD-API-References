---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ColorPalette. تحصل أو تعين قيمة تشير إلى ما إذا تم استخدام لوحة ألوان مضغوطة"
type: docs
weight: 60
url: /ar/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

يحصل أو يعيّن قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` إذا تم استخدام لوحة ألوان مضغوطة؛ وإلا `false`.

## ملاحظات

تعني لوحة الألوان المضغوطة أن الصورة ستحتوي فقط على مدخلات لوحة الألوان المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر ضغطًا وتشغل مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel مدخلًا وستحجز الصورة مساحة أكبر لجميع مدخلات لوحة الألوان الممكنة. ضبط هذه القيمة على true وتغيير مدخلات لوحة الألوان قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث، لذا استخدمها بحذر.

### انظر أيضًا

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


