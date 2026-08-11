---
title: "클래스 Timeline"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline 클래스. 타임라인 옵션 모델"
type: docs
weight: 1980
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

타임라인 옵션 모델.

```csharp
public sealed class Timeline
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Timeline](timeline/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | 활성 프레임 인덱스를 가져옵니다. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | AFSt 값을 가져오거나 설정합니다. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | 프레임 목록을 가져옵니다. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | FsID 값을 가져오거나 설정합니다. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | 루프 수를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | 저장 옵션에 따라 지정된 형식으로 지정된 스트림에 PsdImage와 Timeline 데이터를 저장합니다. |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | 저장 옵션에 따라 지정된 형식으로 지정된 파일 위치에 PsdImage와 Timeline 데이터를 저장합니다. |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | 활성 프레임을 대상 프레임으로 전환합니다. |

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


