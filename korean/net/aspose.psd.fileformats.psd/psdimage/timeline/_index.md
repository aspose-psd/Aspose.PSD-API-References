---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 속성. 이 PsdImage의 타임라인을 가져옵니다"
type: docs
weight: 250
url: /ko/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

이 [`PsdImage`](../)의 `Timeline`을 가져옵니다.

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


