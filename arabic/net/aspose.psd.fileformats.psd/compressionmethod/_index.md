---
title: "التعداد CompressionMethod"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Psd.CompressionMethod. يُعرّف طريقة الضغط المستخدمة لبيانات الصورة."
type: docs
weight: 1630
url: /ar/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

يحدد طريقة الضغط المستخدمة لبيانات الصورة.

```csharp
public enum CompressionMethod : short
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Raw | `0` | بدون ضغط. تُخزن بيانات الصورة كبايتات خام بترتيب RGBA مسطّح. وهذا يعني أنه يتم كتابة جميع بيانات R أولاً، ثم جميع بيانات G، ثم جميع بيانات B وأخيرًا جميع بيانات A. |
| RLE | `1` | بيانات الصورة المضغوطة بتقنية RLE تبدأ بعدد البايتات لكل خطوط المسح (الصفوف × القنوات)، حيث يُخزن كل عدد كقيمة من بايتين. يتبع ذلك البيانات المضغوطة بتقنية RLE، حيث يتم ضغط كل خط مسح على حدة. ضغط RLE هو نفس خوارزمية الضغط المستخدمة في روتين PackBits في ROM ماكintosh ومعيار TIFF. |
| ZipWithoutPrediction | `2` | ZIP بدون توقع. |
| ZipWithPrediction | `3` | ZIP مع توقع. |

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


