---
title: "تعداد CompressionMethod"
type: docs
weight: 2410
url: /ar/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

يحدد طريقة الضغط المستخدمة لبيانات الصورة.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| RAW | بدون ضغط. يتم تخزين بيانات الصورة كبايتات خام بترتيب RGBA مسطح.<br/>            هذا يعني أنه يتم كتابة جميع بيانات R أولاً، ثم جميع بيانات G، ثم جميع بيانات B وأخيراً جميع بيانات A. |
| RLE | يبدأ بيانات الصورة المضغوطة بـ RLE بعدد البايتات لجميع خطوط المسح (الصفوف * القنوات)، حيث يتم تخزين كل عدد كقيمة من بايتين.<br/>            تتبع بيانات RLE المضغوطة، حيث يتم ضغط كل خط مسح على حدة.<br/>            ضغط RLE هو نفس خوارزمية الضغط المستخدمة في روتين ROM الخاص بماكينتوش PackBits ومعيار TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP بدون توقع. |
| ZIP_WITH_PREDICTION | ZIP مع توقع. |
