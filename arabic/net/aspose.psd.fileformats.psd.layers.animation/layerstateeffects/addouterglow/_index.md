---
title: LayerStateEffects.AddOuterGlow
second_title: Aspose.PSD لمرجع .NET API
description: LayerStateEffects طريقة. يضيف تأثير التوهج الخارجي.
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
## LayerStateEffects.AddOuterGlow method

يضيف تأثير التوهج الخارجي.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### قيمة الإرجاع

المثيل الجديد لـ[`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) فصل.

### أمثلة

يوضح الكود التالي دعم التأثيرات في إطارات الخط الزمني.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### أنظر أيضا

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* المجسم [Aspose.PSD](../../../)


