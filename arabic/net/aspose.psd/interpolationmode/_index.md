---
title: "التعداد InterpolationMode"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.InterpolationMode. يحدد تعداد InterpolationMode الخوارزمية المستخدمة عند تكبير أو تصغير الصور أو تدويرها"
type: docs
weight: 5520
url: /ar/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

يحدد تعداد `InterpolationMode` الخوارزمية المستخدمة عند تكبير أو تصغير الصور أو تدويرها.

```csharp
public enum InterpolationMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Invalid | `-1` | وضع الاستيفاء غير صالح. |
| Default | `0` | يحدد الوضع الافتراضي. |
| Low | `1` | يحدد استيفاء منخفض الجودة. |
| High | `2` | يحدد استيفاء عالي الجودة. |
| Bilinear | `3` | يحدد استيفاء ثنائي الخطوط. لا يتم إجراء ترشيح مسبق. هذا الوضع غير مناسب لتقليص الصورة إلى أقل من 50٪ من حجمها الأصلي. |
| Bicubic | `4` | يحدد استيفاء ثلاثي المكعب. لا يتم إجراء ترشيح مسبق. هذا الوضع غير مناسب لتقليص الصورة إلى أقل من 25٪ من حجمها الأصلي. |
| NearestNeighbor | `5` | يحدد استيفاء أقرب جار. |
| HighQualityBilinear | `6` | يحدد استيفاء عالي الجودة، ثنائي الخطوط. يتم إجراء ترشيح مسبق لضمان تقليص عالي الجودة. |
| HighQualityBicubic | `7` | يحدد استيفاء عالي الجودة، ثلاثي المكعب. يتم إجراء ترشيح مسبق لضمان تقليص عالي الجودة. هذا الوضع ينتج أعلى جودة للصور المحوّلة. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


