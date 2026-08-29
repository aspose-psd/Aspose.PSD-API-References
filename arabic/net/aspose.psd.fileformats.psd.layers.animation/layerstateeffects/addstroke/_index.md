---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LayerStateEffects. يضيف تأثير الخط"
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

يضيف تأثير الحد.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fillType | FillType | النوع stroke fill. |

### قيمة الإرجاع

مثال جديد من الفئة [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


