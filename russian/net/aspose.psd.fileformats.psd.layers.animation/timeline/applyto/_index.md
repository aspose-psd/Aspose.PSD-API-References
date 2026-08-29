---
title: "TimeLine.ApplyTo"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод TimeLine. Применить текущие значения таймлайна к входному PsdImage"
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

Применить текущие значения таймлайна к входному [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| psdImage | PsdImage | Изображение psd. |

## Примеры

Класс TimeLine предоставляет высокоуровневую возможность манипулировать таймлайном PsdImage, например изменять задержку кадра или редактировать состояние слоя в конкретном кадре.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Изменить метод освобождения кадра 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Изменить задержку кадра 2
    timeLine.Frames[1].Delay = 15;

    // Изменить непрозрачность 'Layer 1' в кадре 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // переместить 'Layer 1' в левый нижний угол в кадре 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Добавляет новый кадр
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Изменить blendMode слоя 'Layer 1' на кадре 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Применить изменения обратно к экземпляру PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### См. также

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


