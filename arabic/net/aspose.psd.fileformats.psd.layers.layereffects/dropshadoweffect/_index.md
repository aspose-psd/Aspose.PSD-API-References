---
title: Class DropShadowEffect
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect فصل. تأثير طبقة الظل المسقطة
type: docs
weight: 2120
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

تأثير طبقة الظل المسقطة

```csharp
public class DropShadowEffect : IShadowEffect
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | الحصول على الزاوية أو تحديدها بالدرجات . |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | الحصول على أو تحديد وضع المزج . |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | الحصول على اللون أو تحديده . |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | الحصول على أو تحديد المسافة بالبكسل . |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | يحصل على نوع من التأثير |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل مرئيًا. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [يقرع] . |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | الحصول على الضوضاء أو ضبطها . |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | الحصول على التعتيم أو تعيينه . |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | الحصول على أو تعيين قيمة التمويه بالبكسل. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | الحصول على الكثافة أو تحديدها كنسبة مئوية . |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى [استخدام هذه الزاوية في جميع تأثيرات الطبقة] . |

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

* interface [IShadowEffect](../ishadoweffect/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* المجسم [Aspose.PSD](../../)


