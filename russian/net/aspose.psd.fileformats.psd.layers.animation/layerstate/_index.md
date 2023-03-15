---
title: Class LayerState
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState сорт. Варианты состояния слоя временной шкалы.
type: docs
weight: 1860
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Варианты состояния слоя временной шкалы.

```csharp
public sealed class LayerState
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LayerState](layerstate/)(int) | Инициализирует новый экземпляр`LayerState` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Получает или устанавливает режим смешивания. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Получает или устанавливает включенное состояние. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Получает или задает значение непрозрачности заливки. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Получает или задает значение HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Получает или задает идентификатор. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Получает или задает значение непрозрачности. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Получает или задает смещение положения слоя относительно фактического положения слоя. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Получает эффекты состояния слоя. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Получает или задает значение VerticalFXRf. |

### Примеры

Класс TimeLine дает высокоуровневую возможность манипулировать временной шкалой PsdImage, например, изменять задержку кадра или редактировать состояние слоя в конкретном кадре.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Изменяем метод удаления кадра 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Изменить задержку кадра 2
    timeLine.Frames[1].Delay = 15;

    // Изменяем непрозрачность «Слоя 1» на кадре 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // перемещаем 'Слой 1' в левый нижний угол кадра 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Добавляет новый кадр
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Изменяем режим смешивания «Слой 1» на кадре 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Применить изменения к экземпляру PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* сборка [Aspose.PSD](../../)


