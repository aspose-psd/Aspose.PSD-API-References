---
title: "LayerStateEffects.AddDropShadow"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LayerStateEffects. يضيف تأثير الظل المنسدل"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddDropShadow method

يضيف تأثير الظل المنسدل.

```csharp
public DropShadowEffect AddDropShadow()
```

### قيمة الإرجاع

مثال جديد من الفئة [`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


