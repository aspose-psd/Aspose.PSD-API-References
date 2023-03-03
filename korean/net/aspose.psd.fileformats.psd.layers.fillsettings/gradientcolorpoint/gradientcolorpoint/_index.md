---
title: GradientColorPoint.GradientColorPoint
second_title: .NET API 참조용 Aspose.PSD
description: GradientColorPoint 건설자. 의 새 인스턴스를 초기화합니다.GradientColorPoint 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
## GradientColorPoint() {#constructor}

의 새 인스턴스를 초기화합니다.[`GradientColorPoint`](../) 클래스.

```csharp
public GradientColorPoint()
```

### 또한보십시오

* class [GradientColorPoint](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* 집회 [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`GradientColorPoint`](../) 클래스.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| color | Color | 그라디언트의 색상 포인트. |
| location | Int32 | 그라데이션에서 색상 포인트의 위치입니다. |
| medianPointLocation | Int32 | 중간 그라데이션 점 위치입니다. |

### 예

다음 예제는 레이어에서 GradientOverlayEffect 효과 객체를 생성/편집하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// 레이어에서 그래디언트 오버레이 효과를 생성/가져오고 편집합니다.
using (var psdImage = (PsdImage)Image.Load(sourceFilePath, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    BlendingOptions layerBlendOptions = psdImage.Layers[1].BlendingOptions;
    GradientOverlayEffect gradientOverlayEffect = null;

    // 레이어에서 GradientOverlayEffect를 검색합니다.
    foreach (ILayerEffect effect in layerBlendOptions.Effects)
    {
        gradientOverlayEffect = effect as GradientOverlayEffect;
        if (gradientOverlayEffect != null)
        {
            break;
        }
    }

    if (gradientOverlayEffect == null)
    {
        // 존재하지 않는 경우 새로운 GradientOverlayEffect를 생성할 수 있습니다.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // 효과에 약간의 투명도를 추가합니다.
    gradientOverlayEffect.Opacity = 200;

    // 그래디언트 효과의 혼합 모드를 변경합니다.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // 그래디언트 오버레이 설정을 구성하기 위해 GradientFillSettings 개체를 가져옵니다.
    GradientFillSettings settings = gradientOverlayEffect.Settings;

    // 두 가지 색상으로 새 그래디언트를 설정합니다.
    settings.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // 그래디언트의 기울기를 80도로 설정합니다.
    settings.Angle = 80;

    // 그래디언트 효과를 최대 150%까지 조정합니다.
    settings.Scale = 150;

    // 그래디언트 유형을 설정합니다.
    settings.GradientType = GradientType.Linear;

    // 각 투명도 포인트에서 불투명도를 100%로 설정하여 그래디언트를 불투명하게 만듭니다.
    settings.TransparencyPoints[0].Opacity = 100;
    settings.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### 또한보십시오

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientcolorpoint/)
* 집회 [Aspose.PSD](../../../)


