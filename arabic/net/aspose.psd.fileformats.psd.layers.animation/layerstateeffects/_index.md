---
title: "الفئة LayerStateEffects"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects. تأثيرات حالة الطبقة"
type: docs
weight: 1970
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
{{< psd/tize >}}
## LayerStateEffects class

تأثيرات حالة الطبقة.

```csharp
public class LayerStateEffects
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | يسترجع تأثيرات الطبقة. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه الحالة مرئية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | يضيف تأثير تغطية اللون. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | يضيف تأثير الظل المنسدل. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | يضيف تأثير تغطية التدرج. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | يضيف تأثير الظل الداخلي. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | يضيف تأثير التوهج الخارجي. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | يضيف تأثير تغطية النمط. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | يضيف تأثير الحد. |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | يمسح جميع تأثيرات نمط الطبقة. |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | يزيل تأثير الطبقة عند الفهرس المحدد. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


