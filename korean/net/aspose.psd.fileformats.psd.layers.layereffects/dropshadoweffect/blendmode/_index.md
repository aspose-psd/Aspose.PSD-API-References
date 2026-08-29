---
title: "DropShadowEffect.BlendMode"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "DropShadowEffect 속성. 혼합 모드를 가져오거나 설정합니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/
---
{{< psd/tize >}}
## DropShadowEffect.BlendMode property

블렌드 모드를 가져오거나 설정합니다.

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

블렌드 모드.

## 예제

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


