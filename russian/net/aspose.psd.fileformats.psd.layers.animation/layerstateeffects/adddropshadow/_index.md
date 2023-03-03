---
title: LayerStateEffects.AddDropShadow
second_title: Справочник по Aspose.PSD для .NET API
description: LayerStateEffects метод. Добавляет эффект тени.
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
## LayerStateEffects.AddDropShadow method

Добавляет эффект тени.

```csharp
public DropShadowEffect AddDropShadow()
```

### Возвращаемое значение

Новый экземпляр[`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) сорт.

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* сборка [Aspose.PSD](../../../)


