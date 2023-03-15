---
title: Enum LayerEffectsTypes
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes 열거형. 레이어 혼합 효과.
type: docs
weight: 2660
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

레이어 혼합 효과.

```csharp
public enum LayerEffectsTypes
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| DropShadow | `0` | 그림자. |
| OuterGlow | `1` | 외부 광선. |
| PatternOverlay | `2` | 패턴 오버레이. |
| GradientOverlay | `3` | 그래디언트 오버레이. |
| ColorOverlay | `4` | 색상 오버레이. |
| Satin | `5` | 새틴 효과 유형. |
| InnerGlow | `6` | 내면의 빛. |
| InnerShadow | `7` | 내부 그림자. |
| Stroke | `8` | 스트로크. |
| BevelEmboss | `9` | 베벨 엠보스. |

### 예

다음 코드는 ILayerEffect.EffectType 속성의 지원을 보여줍니다.

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
            // 걸렸다
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* 집회 [Aspose.PSD](../../)


