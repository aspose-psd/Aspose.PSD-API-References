---
title: "LayerState.BlendMode"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство LayerState. Получает или задает режим смешивания"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/
---
{{< psd/tize >}}
## LayerState.BlendMode property

Получает или задает режим смешивания.

```csharp
public BlendMode BlendMode { get; set; }
```

## Примеры

Класс Timeline предоставляет высокоуровневую возможность управлять временной шкалой PsdImage, например изменять задержку кадра или редактировать состояние слоя в конкретном кадре.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Изменить метод освобождения кадра 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Изменить задержку кадра 2
    timeline.Frames[1].Delay = 15;

    // Изменить непрозрачность 'Layer 1' в кадре 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // переместить 'Layer 1' в левый нижний угол в кадре 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Добавляет новый кадр
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Изменить blendMode слоя 'Layer 1' на кадре 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Применить изменения обратно к экземпляру PsdImage
    psdImage.Save(outputPsd);
}
```

### См. также

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


