---
title: DropShadowEffect.IsVisible
second_title: .NET API 참조용 Aspose.PSD
description: DropShadowEffect 재산. 이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다.
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool IsVisible { get; set; }
```

### 자산 가치

`진실` 이 인스턴스가 표시되면; 그렇지 않으면,`거짓` .

### 예

다음 코드는 DropShadowEffect의 Opacity 속성을 사용하는 방법을 보여줍니다.

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

    // 불투명도가 20인 예
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // 불투명도가 20인 예0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### 또한보십시오

* class [DropShadowEffect](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* 집회 [Aspose.PSD](../../../)


