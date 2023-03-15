---
title: Class TimeLine
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine сорт. Модель опций временной шкалы.
type: docs
weight: 1880
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

Модель опций временной шкалы.

```csharp
public sealed class TimeLine
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TimeLine](timeline/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | Получает или задает индекс активного кадра. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Получает или задает значение AFSt. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Получает список кадров. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Получает или задает значение FsID. |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | Получает или задает массив идентификаторов слоев. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Получает или задает количество циклов. |

## Методы

| Имя | Описание |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | Создает новый экземпляр`TimeLine` , инициализируется из ввода[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | Применить текущие значения временной шкалы к входным данным[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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


