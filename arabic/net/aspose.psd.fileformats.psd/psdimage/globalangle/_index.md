---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PsdImage. يحصل على أو يعيّن الزاوية العامة"
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

يحصل أو يضبط الزاوية العامة.

```csharp
public int GlobalAngle { get; set; }
```

## أمثلة

يوضح الشيفرة التالية دعم الخاصية PsdImage.GlobalAngle لتغيير قيمة الزاوية العامة.

```csharp
[C#]

// عند كون الخاصية DropShadowEffect.UseGlobalLight مساوية لـ 'true'، يستخدم كائن DropShadowEffect قيمة الزاوية من الخاصية PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### انظر أيضًا

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


