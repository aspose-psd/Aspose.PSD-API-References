---
title: "Timeline.SwitchActiveFrame"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Timeline. Переключает активный кадр на целевой"
type: docs
weight: 80
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Переключает активный кадр на целевой.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | Индекс целевого кадра. |

### Исключения

| исключение | условие |
| --- | --- |
| IndexOutOfRangeException | Новый индекс активного кадра должен находиться в диапазоне количества кадров. |

## Примеры

Следующий код демонстрирует новый подход к работе с Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Добавьте ещё один кадр
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### См. также

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


