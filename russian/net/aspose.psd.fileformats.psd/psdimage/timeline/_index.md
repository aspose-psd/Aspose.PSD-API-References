---
title: "PsdImage.Timeline"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PsdImage. Возвращает Timeline этого PsdImage."
type: docs
weight: 250
url: /ru/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Получает `Timeline` этого [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
```

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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


