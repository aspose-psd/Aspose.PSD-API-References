---
title: "Timeline.ActiveFrameIndex"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство Timeline. Возвращает индекс активного кадра"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Получает индекс активного кадра.

```csharp
public int ActiveFrameIndex { get; }
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

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


