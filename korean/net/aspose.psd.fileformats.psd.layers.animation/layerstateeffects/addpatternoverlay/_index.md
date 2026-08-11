---
title: "LayerStateEffects.AddPatternOverlay"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LayerStateEffects 메서드. 패턴 오버레이 효과를 추가합니다"
type: docs
weight: 80
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddPatternOverlay method

패턴 오버레이 효과를 추가합니다.

```csharp
public PatternOverlayEffect AddPatternOverlay()
```

### 반환 값

새 인스턴스인 [`PatternOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/) 클래스.

## 예제

다음 코드는 타임라인 프레임에서 효과 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### 또 보기

* class [PatternOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


