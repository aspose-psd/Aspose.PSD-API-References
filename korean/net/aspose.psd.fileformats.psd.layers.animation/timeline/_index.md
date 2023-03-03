---
title: Class TimeLine
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine 수업. 타임라인 옵션 모델.
type: docs
weight: 1880
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

타임라인 옵션 모델.

```csharp
public sealed class TimeLine
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TimeLine](timeline/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | 활성 프레임 인덱스를 가져오거나 설정합니다. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | AFSt 값을 가져오거나 설정합니다. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | 프레임 목록을 가져옵니다. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | FsID 값을 가져오거나 설정합니다. |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | 레이어 ID 배열을 가져오거나 설정합니다. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | 루프 수를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | 의 새 인스턴스를 만듭니다.`TimeLine` , 입력에서 초기화[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | 현재 타임 라인 값을 입력에 적용[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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


