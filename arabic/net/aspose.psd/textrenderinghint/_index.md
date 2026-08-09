---
title: "التعداد TextRenderingHint"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.TextRenderingHint. يحدد جودة عرض النص."
type: docs
weight: 6200
url: /ar/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

يحدد جودة عرض النص.

```csharp
public enum TextRenderingHint
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| SystemDefault | `0` | يتم رسم كل حرف باستخدام صورة البكسل الخاصة بالرمز، مع تلميح العرض الافتراضي للنظام. سيتم رسم النص باستخدام أي إعدادات تنعيم الخط التي يختارها المستخدم للنظام. |
| SingleBitPerPixelGridFit | `1` | يتم رسم كل حرف باستخدام صورة البكسل الخاصة بالرمز. يُستخدم التلميح لتحسين مظهر الحرف على الجذوع والانحناءات. |
| SingleBitPerPixel | `2` | يتم رسم كل حرف باستخدام صورة البكسل الخاصة بالرمز. لا يُستخدم التلميح. |
| AntiAliasGridFit | `3` | يتم رسم كل حرف باستخدام صورة البكسل المضادة للتعرج للرمز مع التلميح. جودة أفضل بكثير بفضل مضاد التعرج، لكن بتكلفة أداء أعلى. |
| AntiAlias | `4` | يتم رسم كل حرف باستخدام صورة البكسل المضادة للتعرج للرمز دون التلميح. جودة أفضل بفضل مضاد التعرج. قد تكون اختلافات عرض الجذع ملحوظة لأن التلميح مُعطل. |
| ClearTypeGridFit | `5` | يتم رسم كل حرف باستخدام صورة البكسل ClearType للرمز مع التلميح. أعلى إعداد للجودة. يُستخدم للاستفادة من ميزات خط ClearType. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


