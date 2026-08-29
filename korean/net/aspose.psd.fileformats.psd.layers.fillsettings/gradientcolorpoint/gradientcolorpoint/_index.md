---
title: "GradientColorPoint.GradientColorPoint"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GradientColorPoint 생성자. GradientColorPoint 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/gradientcolorpoint/
---
{{< psd/tize >}}
## GradientColorPoint() {#constructor}

`[`GradientColorPoint`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public GradientColorPoint()
```

### 또 보기

* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)

---

## GradientColorPoint(Color, int, int) {#constructor_1}

`[`GradientColorPoint`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public GradientColorPoint(Color color, int location, int medianPointLocation)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 색상 | 색상 | 그라디언트상의 색상 점. |
| 위치 | Int32 | 그라디언트에서 색상 포인트의 위치. |
| medianPointLocation | Int32 | 중간 그라디언트 포인트 위치. |

## 예제

다음 예제는 레이어에서 GradientOverlayEffect 효과 객체를 생성/편집하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "psdnet256.psd";
string outputFilePath = "psdnet256.psd_output.psd";

// 레이어에서 그라디언트 오버레이 효과를 생성/획득하고 편집합니다.
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
        // GradientOverlayEffect가 존재하지 않을 경우 새로 만들 수 있습니다.
        gradientOverlayEffect = layerBlendOptions.AddGradientOverlay();
    }

    // 효과에 약간의 투명성을 추가합니다.
    gradientOverlayEffect.Opacity = 200;

    // 그라디언트 효과의 블렌드 모드를 변경합니다.
    gradientOverlayEffect.BlendMode = BlendMode.Hue;

    // 그라디언트 오버레이 설정을 구성하기 위해 GradientFillSettings 객체를 가져옵니다.
    GradientFillSettings settings = (GradientFillSettings)gradientOverlayEffect.Settings;
    SolidGradient solidGradient = (SolidGradient)settings.Gradient;

    // 두 가지 색상으로 새로운 그라디언트를 설정합니다.
    solidGradient.ColorPoints = new IGradientColorPoint[]
    {
        new GradientColorPoint(Color.GreenYellow, 0, 50),
        new GradientColorPoint(Color.BlueViolet, 4096, 50),
    };

    // 그라디언트를 80도 각도로 기울입니다.
    settings.Angle = 80;

    // 그라디언트 효과를 최대 150%까지 확대합니다.
    settings.Scale = 150;

    // 그라디언트 유형을 설정합니다.
    settings.GradientType = GradientType.Linear;

    // 각 투명도 지점에서 불투명도를 100%로 설정하여 그라디언트를 불투명하게 만듭니다.
    solidGradient.TransparencyPoints[0].Opacity = 100;
    solidGradient.TransparencyPoints[1].Opacity = 100;

    psdImage.Save(outputFilePath);
}
```

### 또 보기

* struct [Color](../../../aspose.psd/color/)
* class [GradientColorPoint](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


