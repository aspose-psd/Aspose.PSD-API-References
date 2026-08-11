---
title: "클래스 DropShadowEffect"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect 클래스. 드롭 섀도우 레이어 효과"
type: docs
weight: 2310
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
{{< psd/tize >}}
## DropShadowEffect class

드롭 섀도우 레이어 효과

```csharp
public class DropShadowEffect : IShadowEffect
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | 각도를 도 단위로 가져오거나 설정합니다. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | 블렌드 모드를 가져오거나 설정합니다. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | 색상을 가져오거나 설정합니다. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | 거리를 픽셀 단위로 가져오거나 설정합니다. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | 효과 유형을 가져옵니다. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | 이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | 노크아웃 여부를 나타내는 값을 가져오거나 설정합니다([knocks out]). |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | 노이즈를 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | 불투명도를 가져오거나 설정합니다. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | 블러 값을 픽셀 단위로 가져오거나 설정합니다. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | 강도를 백분율로 가져오거나 설정합니다. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | 값을 가져오거나 설정하여 [use this angle in all of the layer effects] 여부를 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/geteffectbounds/)(Rectangle, int) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |

## 예제

다음 코드는 전역 각도 값을 변경하기 위한 PsdImage.GlobalAngle 속성 지원을 보여줍니다.

```csharp
[C#]

// DropShadowEffect.UseGlobalLight 속성이 'true'이면, DropShadowEffect 객체는 PsdImage.GlobalAngle 속성의 각도 값을 사용합니다.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

다음 코드는 DropShadowEffect의 Opacity 속성 사용을 보여줍니다.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Opacity = 20인 예시
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Opacity = 200인 예시
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### 또 보기

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


