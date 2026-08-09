---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdColorPalette. تحصل على قيمة تشير إلى ما إذا كانت اللوحة مضغوطة"
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

يحصل على قيمة تشير ما إذا كانت لوحة الألوان مضغوطة.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` إذا كانت اللوحة مضغوطة؛ وإلا `false`.

## ملاحظات

تعني لوحة الألوان المضغوطة أن الصورة ستحتوي فقط على مدخلات لوحة الألوان المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر ضغطًا وتشغل مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel مدخلًا وستحجز الصورة مساحة أكبر لجميع مدخلات لوحة الألوان الممكنة. ضبط هذه القيمة على true وتغيير مدخلات لوحة الألوان قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث، لذا استخدمها بحذر.

### انظر أيضًا

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


