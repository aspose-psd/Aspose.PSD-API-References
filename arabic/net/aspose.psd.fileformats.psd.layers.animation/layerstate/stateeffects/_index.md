---
title: LayerState.StateEffects
second_title: Aspose.PSD لمرجع .NET API
description: LayerState ملكية. يحصل على تأثيرات حالة الطبقة .
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

يحصل على تأثيرات حالة الطبقة .

```csharp
public LayerStateEffects StateEffects { get; }
```

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

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* المجسم [Aspose.PSD](../../../)


