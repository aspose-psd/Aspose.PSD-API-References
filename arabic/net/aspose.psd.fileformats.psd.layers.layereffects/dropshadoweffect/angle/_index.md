---
title: DropShadowEffect.Angle
second_title: Aspose.PSD لمرجع .NET API
description: DropShadowEffect ملكية. الحصول على الزاوية أو تحديدها بالدرجات .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

الحصول على الزاوية أو تحديدها بالدرجات .

```csharp
public int Angle { get; set; }
```

### Property_Value

الزاوية .

### أمثلة

توضح التعليمة البرمجية التالية استخدام خاصية Opacity لـ DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // مثال مع التعتيم = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // مثال مع التعتيم = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### أنظر أيضا

* class [DropShadowEffect](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* المجسم [Aspose.PSD](../../../)


