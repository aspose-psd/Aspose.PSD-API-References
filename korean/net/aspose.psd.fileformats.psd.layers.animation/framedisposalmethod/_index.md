---
title: Enum FrameDisposalMethod
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod 열거형. 프레임 폐기 방법은 다음 프레임을 표시하기 전에 현재 프레임을 버릴지 여부를 지정합니다. 현재 프레임이 다음 프레임의 투명 영역을 통해 표시되는지 여부를 지정하려면 배경 투명도를 포함하는 애니메이션에 대한 폐기 방법을 선택합니다.
type: docs
weight: 1850
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

프레임 폐기 방법은 다음 프레임을 표시하기 전에 현재 프레임을 버릴지 여부를 지정합니다. 현재 프레임이 다음 프레임의 투명 영역을 통해 표시되는지 여부를 지정하려면 배경 투명도를 포함하는 애니메이션에 대한 폐기 방법을 선택합니다.

```csharp
public enum FrameDisposalMethod
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Automatic | `0` | 다음 프레임에 레이어 투명도가 포함된 경우 현재 프레임을 버리고 현재 프레임의 폐기 방법을 자동으로 결정합니다. 대부분의 애니메이션에서 자동 옵션(기본값)은 원하는 결과를 생성합니다. |
| DoNotDispose | `1` | 다음 프레임이 디스플레이에 추가될 때 현재 프레임을 유지합니다. 현재 프레임(및 이전 프레임)은 다음 프레임의 투명 영역을 통해 표시될 수 있습니다. |
| Dispose | `2` | 다음 프레임이 표시되기 전에 디스플레이에서 현재 프레임을 버립니다. 항상 단일 프레임만 표시됩니다(현재 프레임은 다음 프레임의 투명 영역을 통해 나타나지 않음). |

### 예

TimeLine 클래스는 특정 프레임에서 프레임 지연 변경 또는 레이어 상태 편집과 같이 PsdImage의 타임라인을 조작하는 고급 기능을 제공합니다.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // 프레임 1의 dispose 방식 변경
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // 프레임 2의 지연 변경
    timeLine.Frames[1].Delay = 15;

    // 프레임 2에서 '레이어 1'의 불투명도 변경
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // '레이어 1'을 프레임 3의 왼쪽 아래 모서리로 이동
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // 새 프레임 추가
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // 프레임 4에서 'Layer 1'의 blendMode 변경
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 변경 사항을 PsdImage 인스턴스에 다시 적용
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* 집회 [Aspose.PSD](../../)


