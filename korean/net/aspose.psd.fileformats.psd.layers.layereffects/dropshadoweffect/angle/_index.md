---
title: "DropShadowEffect.Angle"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "DropShadowEffect 속성. 각도를 도 단위로 가져오거나 설정합니다."
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
{{< psd/tize >}}
## DropShadowEffect.Angle property

각도를 도 단위로 가져오거나 설정합니다.

```csharp
public int Angle { get; set; }
```

### Property Value

각도입니다.

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

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


