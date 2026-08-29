---
title: "Класс LayerState"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState. Параметры состояния слоя на временной шкале."
type: docs
weight: 1960
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

Параметры состояния слоя временной шкалы.

```csharp
public sealed class LayerState
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LayerState](layerstate/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Получает или задает режим смешивания. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Получает или задает состояние включения. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Получает или задает значение непрозрачности заливки. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Получает или задает значение HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Получает или задает идентификатор слоя. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Получает или задает значение непрозрачности. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Получает или задает смещение позиции слоя относительно фактической позиции слоя. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Получает эффекты состояния слоя. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Получает или задает значение VerticalFXRf. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


