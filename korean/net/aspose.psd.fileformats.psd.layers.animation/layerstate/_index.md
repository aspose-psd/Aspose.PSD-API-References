---
title: Class LayerState
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState 수업. 타임 라인 레이어 상태의 옵션입니다.
type: docs
weight: 1860
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

타임 라인 레이어 상태의 옵션입니다.

```csharp
public sealed class LayerState
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LayerState](layerstate/)(int) | 의 새 인스턴스를 초기화합니다.`LayerState` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | 블렌 모드를 가져오거나 설정합니다. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | 활성화된 상태를 가져오거나 설정합니다. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | 채우기 불투명도 값을 가져오거나 설정합니다. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | HorizontalFXRf 값을 가져오거나 설정합니다. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | id. 를 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | 불투명도 값을 가져오거나 설정합니다. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | 실제 레이어 위치와 관련된 레이어 위치 오프셋을 가져오거나 설정합니다. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | 레이어 상태 효과를 가져옵니다. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | VerticalFXRf 값을 가져오거나 설정합니다. |

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


