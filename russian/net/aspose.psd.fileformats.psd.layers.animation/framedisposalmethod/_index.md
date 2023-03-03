---
title: Enum FrameDisposalMethod
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod перечисление. Метод удаления кадров указывает следует ли отбрасывать текущий кадр перед отображением следующего кадра. Вы выбираете метод удаления для анимаций включающих прозрачность фона чтобы указать будет ли кадр current виден через прозрачные области следующего кадра.
type: docs
weight: 1850
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

Метод удаления кадров указывает, следует ли отбрасывать текущий кадр перед отображением следующего кадра. Вы выбираете метод удаления для анимаций, включающих прозрачность фона, чтобы указать, будет ли кадр current виден через прозрачные области следующего кадра.

```csharp
public enum FrameDisposalMethod
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Automatic | `0` | Автоматически определяет метод удаления для текущего кадра, отбрасывая текущий кадр, если следующий кадр содержит прозрачность слоя. Для большинства анимаций параметр «Автоматически» (по умолчанию) дает желаемые результаты. |
| DoNotDispose | `1` | Сохраняет текущий кадр при добавлении следующего кадра на дисплей. Текущий кадр (и предшествующие кадры) могут отображаться сквозь прозрачные области следующего кадра. |
| Dispose | `2` | Отбрасывает текущий кадр с экрана перед отображением следующего кадра. В каждый момент времени отображается только один кадр (и текущий кадр не виден через прозрачные области следующего кадра). |

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


