---
title: "클래스 Frame"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame 클래스. 타임라인 프레임 항목 옵션"
type: docs
weight: 1940
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

타임라인 프레임 항목 옵션.

```csharp
public sealed class Frame
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Frame](frame/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | 프레임 지연 값을 센타초 단위로 가져오거나 설정합니다. 예를 들어, 1초는 100센타초를 포함합니다. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | 프레임의 폐기 방법을 가져오거나 설정합니다. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | 프레임 ID를 가져오거나 설정합니다. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | 프레임의 레이어 상태를 가져오거나 설정합니다. |

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


