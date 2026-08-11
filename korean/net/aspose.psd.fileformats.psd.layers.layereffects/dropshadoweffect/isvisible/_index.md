---
title: "DropShadowEffect.IsVisible"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "DropShadowEffect 속성. 이 인스턴스가 보이는지 여부를 나타내는 값을 가져오거나 설정합니다"
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true`이면 이 인스턴스가 표시됩니다; 그렇지 않으면 `false`.

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


