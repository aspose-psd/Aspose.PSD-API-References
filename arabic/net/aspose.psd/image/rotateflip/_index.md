---
title: "Image.RotateFlip"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Image. تدور أو تقلب أو تدور وتقلب الصورة"
type: docs
weight: 230
url: /ar/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

يدور أو يقلب أو يدور ويقلب الصورة.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع دوران القلب. |

## أمثلة

يوضح هذا المثال استخدام عملية Rotate على صورة. يقوم المثال بتحميل ملف صورة موجود من موقع على القرص ويؤدي عملية Rotate على الصورة وفقًا لقيمة تعداد Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//إنشاء نسخة من الفئة image وتهيئتها بملف صورة موجود عبر مسار الملف
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //دوّر الصورة بزاوية 180 درجة حول المحور X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // احفظ جميع التغييرات.
    image.Save();
}
```

### انظر أيضًا

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


