---
title: DropShadowEffect.Color
second_title: Aspose.PSD لمرجع .NET API
description: DropShadowEffect ملكية. الحصول على اللون أو تحديده .
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/
---
## DropShadowEffect.Color property

الحصول على اللون أو تحديده .

```csharp
public Color Color { get; set; }
```

### Property_Value

اللون .

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

* struct [Color](../../../aspose.psd/color/)
* class [DropShadowEffect](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* المجسم [Aspose.PSD](../../../)


