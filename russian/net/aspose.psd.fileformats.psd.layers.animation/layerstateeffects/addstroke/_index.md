---
title: "LayerStateEffects.AddStroke"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод LayerStateEffects. Добавляет эффект обводки"
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Добавляет эффект обводки.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillType | FillType | Тип штриховой заливки. |

### Возвращаемое значение

Новый экземпляр класса [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/).

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


