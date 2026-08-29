---
title: "LayerStateEffects.AddInnerShadow"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LayerStateEffects. تضيف تأثير الظل الداخلي"
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddInnerShadow method

يضيف تأثير الظل الداخلي.

```csharp
public InnerShadowEffect AddInnerShadow()
```

### قيمة الإرجاع

مثال جديد من الفئة [`InnerShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/).

## أمثلة

الكود التالي يوضح دعم التأثيرات في إطارات Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### انظر أيضًا

* class [InnerShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


