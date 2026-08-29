---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Timeline 메서드. 활성 프레임을 대상 프레임으로 전환합니다"
type: docs
weight: 80
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

활성 프레임을 대상 프레임으로 전환합니다.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | 대상 프레임 인덱스입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| IndexOutOfRangeException | 활성 프레임의 새 인덱스는 프레임 수 범위 내에 있어야 합니다. |

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


