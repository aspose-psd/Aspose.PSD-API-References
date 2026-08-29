---
title: "LayerStateEffects.AddOuterGlow"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод LayerStateEffects. Добавляет эффект внешнего свечения"
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
{{< psd/tize >}}
## LayerStateEffects.AddOuterGlow method

Добавляет эффект внешнего свечения.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Возвращаемое значение

Новый экземпляр класса [`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/).

## Примеры

Следующий код демонстрирует поддержку эффектов в кадрах Timeline.

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

### См. также

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


