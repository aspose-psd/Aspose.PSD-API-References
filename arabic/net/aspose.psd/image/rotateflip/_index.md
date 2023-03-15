---
title: Image.RotateFlip
second_title: Aspose.PSD لمرجع .NET API
description: Image طريقة. يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها.
type: docs
weight: 220
url: /ar/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع تدوير الوجه. |

### أمثلة

يوضح هذا المثال استخدام عملية التدوير على صورة. مثال يقوم بتحميل ملف صورة موجود من بعض مواقع القرص ويقوم بإجراء عملية التدوير على الصورة وفقًا لقيمة Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

// إنشاء مثيل لفئة الصورة وتهيئته بملف صورة موجود من خلال مسار الملف
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // قم بتدوير الصورة 180 درجة حول المحور X.
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // احفظ جميع التغييرات.
    image.Save();
}
```

### أنظر أيضا

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)


