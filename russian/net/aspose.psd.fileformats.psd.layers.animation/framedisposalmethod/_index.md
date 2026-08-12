---
title: "Перечисление FrameDisposalMethod"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod. Метод удаления кадра указывает, следует ли отбрасывать текущий кадр перед отображением следующего кадра. Вы выбираете метод удаления для анимаций, включающих прозрачность фона, чтобы указать, будет ли текущий кадр виден через прозрачные области следующего кадра."
type: docs
weight: 1950
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

Метод утилизации кадра определяет, следует ли удалять текущий кадр перед отображением следующего кадра. Вы выбираете метод утилизации для анимаций, включающих прозрачность фона, чтобы указать, будет ли текущий кадр виден через прозрачные области следующего кадра.

```csharp
public enum FrameDisposalMethod
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Automatic | `0` | Определяет метод удаления текущего кадра автоматически, отбрасывая текущий кадр, если следующий кадр содержит прозрачность слоев. Для большинства анимаций автоматический вариант (по умолчанию) дает желаемый результат. |
| DoNotDispose | `1` | Сохраняет текущий кадр при добавлении следующего кадра в отображение. Текущий кадр (и предшествующие кадры) могут просвечивать через прозрачные области следующего кадра. |
| Dispose | `2` | Отбрасывает текущий кадр из отображения перед тем, как будет показан следующий кадр. В любой момент отображается только один кадр (и текущий кадр не просвечивает через прозрачные области следующего кадра). |

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


