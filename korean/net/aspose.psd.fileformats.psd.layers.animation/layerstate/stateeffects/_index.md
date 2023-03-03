---
title: LayerState.StateEffects
second_title: .NET API 참조용 Aspose.PSD
description: LayerState 재산. 레이어 상태 효과를 가져옵니다.
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

레이어 상태 효과를 가져옵니다.

```csharp
public LayerStateEffects StateEffects { get; }
```

### 예

다음 코드는 타임라인 프레임의 효과 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### 또한보십시오

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* 집회 [Aspose.PSD](../../../)


