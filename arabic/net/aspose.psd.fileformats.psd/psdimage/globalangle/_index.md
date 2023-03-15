---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD لمرجع .NET API
description: PsdImage ملكية. الحصول على الزاوية العامة أو تحديدها .
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

الحصول على الزاوية العامة أو تحديدها .

```csharp
public int GlobalAngle { get; set; }
```

### أمثلة

توضح التعليمة البرمجية التالية دعم الخاصية PsdImage.GlobalAngle لتغيير قيمة الزاوية العامة.

```csharp
[C#]

// عندما تكون خاصية DropShadowEffect.UseGlobalLight هي "true" ، فإن كائن DropShadowEffect يستخدم قيمة الزاوية من خاصية PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### أنظر أيضا

* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)


