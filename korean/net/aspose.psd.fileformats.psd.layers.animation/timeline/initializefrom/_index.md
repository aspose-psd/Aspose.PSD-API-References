---
title: "TimeLine.InitializeFrom"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "TimeLine 메서드. 입력 PsdImage에서 초기화된 새로운 TimeLine 인스턴스를 생성합니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/
---
{{< psd/tize >}}
## TimeLine.InitializeFrom method

입력 [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/)에서 초기화된 새로운 [`TimeLine`](../) 인스턴스를 생성합니다.

```csharp
public static TimeLine InitializeFrom(PsdImage psdImage)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| psdImage | PsdImage | psd 이미지입니다. |

### 반환 값

입력 [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/)에서 초기화된 새로운 [`TimeLine`](../) 인스턴스입니다.

## 예제

TimeLine 클래스는 PsdImage의 타임라인을 조작할 수 있는 고수준 기능을 제공하며, 예를 들어 프레임 지연을 변경하거나 특정 프레임의 레이어 상태를 편집할 수 있습니다.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // 프레임 1의 폐기 방법을 변경합니다
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // 프레임 2의 지연을 변경합니다
    timeLine.Frames[1].Delay = 15;

    // 프레임 2에서 'Layer 1'의 불투명도를 변경합니다
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 프레임 3에서 'Layer 1'을 좌하단 모서리로 이동합니다
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // 새 프레임을 추가합니다
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // 프레임 4에서 'Layer 1'의 blendMode를 변경합니다
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 변경 사항을 PsdImage 인스턴스에 적용합니다
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### 또 보기

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


