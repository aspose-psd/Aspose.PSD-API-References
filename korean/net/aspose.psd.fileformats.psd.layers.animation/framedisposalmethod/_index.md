---
title: "Enum FrameDisposalMethod"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod 열거형. 프레임 폐기 방법은 다음 프레임을 표시하기 전에 현재 프레임을 폐기할지 여부를 지정합니다. 배경 투명성을 포함하는 애니메이션의 경우 현재 프레임이 다음 프레임의 투명 영역을 통해 보일지 여부를 지정하기 위해 폐기 방법을 선택합니다."
type: docs
weight: 1950
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

프레임 폐기 방법은 다음 프레임을 표시하기 전에 현재 프레임을 폐기할지 여부를 지정합니다. 배경 투명성을 포함하는 애니메이션의 경우, 현재 프레임이 다음 프레임의 투명 영역을 통해 보일지 여부를 지정하기 위해 폐기 방법을 선택합니다.

```csharp
public enum FrameDisposalMethod
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Automatic | `0` | 다음 프레임에 레이어 투명성이 포함된 경우 현재 프레임을 자동으로 폐기 방법을 결정하여 현재 프레임을 폐기합니다. 대부분의 애니메이션에서 Automatic 옵션(기본값)이 원하는 결과를 제공합니다. |
| DoNotDispose | `1` | 다음 프레임이 디스플레이에 추가될 때 현재 프레임을 유지합니다. 현재 프레임(및 이전 프레임)은 다음 프레임의 투명 영역을 통해 표시될 수 있습니다. |
| Dispose | `2` | 다음 프레임이 표시되기 전에 현재 프레임을 디스플레이에서 폐기합니다. 언제든지 하나의 프레임만 표시되며(현재 프레임은 다음 프레임의 투명 영역을 통해 나타나지 않습니다). |

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


