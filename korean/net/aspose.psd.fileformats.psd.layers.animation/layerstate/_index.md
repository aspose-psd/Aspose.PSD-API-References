---
title: "Class LayerState"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState 클래스. 타임라인 레이어 상태 옵션"
type: docs
weight: 1960
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

타임라인 레이어 상태 옵션.

```csharp
public sealed class LayerState
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LayerState](layerstate/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | 블렌딩 모드를 가져오거나 설정합니다. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | 활성화 상태를 가져오거나 설정합니다. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | 채우기 불투명도 값을 가져오거나 설정합니다. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | HorizontalFXRf 값을 가져오거나 설정합니다. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | 레이어 ID를 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | 불투명도 값을 가져오거나 설정합니다. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | 실제 레이어 위치와 관련된 레이어 위치 오프셋을 가져오거나 설정합니다. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | 레이어 상태 효과를 가져옵니다. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | VerticalFXRf 값을 가져오거나 설정합니다. |

## 예제

Timeline 클래스는 프레임 지연을 변경하거나 특정 프레임에서 레이어 상태를 편집하는 등 PsdImage의 타임라인을 조작할 수 있는 고수준 기능을 제공합니다.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // 프레임 1의 폐기 방법을 변경합니다
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // 프레임 2의 지연을 변경합니다
    timeline.Frames[1].Delay = 15;

    // 프레임 2에서 'Layer 1'의 불투명도를 변경합니다
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // 프레임 3에서 'Layer 1'을 좌하단 모서리로 이동합니다
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // 새 프레임을 추가합니다
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // 프레임 4에서 'Layer 1'의 blendMode를 변경합니다
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // 변경 사항을 PsdImage 인스턴스에 적용합니다
    psdImage.Save(outputPsd);
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


