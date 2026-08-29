---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Timeline 속성. 활성 프레임 인덱스를 가져옵니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

활성 프레임 인덱스를 가져옵니다.

```csharp
public int ActiveFrameIndex { get; }
```

## 예제

다음 코드는 Timeline을 사용한 새로운 접근 방식을 보여줍니다.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // 프레임을 하나 더 추가합니다.
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### 또 보기

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


