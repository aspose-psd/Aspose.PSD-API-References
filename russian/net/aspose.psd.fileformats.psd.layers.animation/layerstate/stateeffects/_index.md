---
title: LayerState.StateEffects
second_title: Справочник по Aspose.PSD для .NET API
description: LayerState свойство. Получает эффекты состояния слоя.
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Получает эффекты состояния слоя.

```csharp
public LayerStateEffects StateEffects { get; }
```

### Примеры

Следующий код демонстрирует поддержку эффектов в кадрах временной шкалы.

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

### Смотрите также

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* сборка [Aspose.PSD](../../../)


