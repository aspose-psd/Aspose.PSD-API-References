---
title: "열거형 LayerEffectsTypes"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes 열거형. 레이어 블렌딩 효과"
type: docs
weight: 2360
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

레이어 혼합 효과.

```csharp
public enum LayerEffectsTypes
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| DropShadow | `0` | 드롭 섀도우. |
| OuterGlow | `1` | 외부 글로우. |
| PatternOverlay | `2` | 패턴 오버레이. |
| GradientOverlay | `3` | 그라디언트 오버레이. |
| ColorOverlay | `4` | 컬러 오버레이. |
| Satin | `5` | 새틴 효과 유형. |
| InnerGlow | `6` | 내부 글로우. |
| InnerShadow | `7` | 내부 섀도우. |
| Stroke | `8` | 스트로크. |
| BevelEmboss | `9` | 베벨 엠보스. |

## 예제

다음 코드는 ILayerEffect.EffectType 속성 지원을 보여줍니다.

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // 포착되었습니다
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


