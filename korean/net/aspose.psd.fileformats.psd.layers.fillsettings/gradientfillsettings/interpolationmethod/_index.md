---
title: "GradientFillSettings.InterpolationMethod"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "GradientFillSettings 속성. 그라디언트의 보간 방법을 가져오거나 설정합니다"
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/interpolationmethod/
---
{{< psd/tize >}}
## GradientFillSettings.InterpolationMethod property

그라디언트에 대한 보간 방법을 가져오거나 설정합니다.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## 예제

다음 코드는 Smooth 메서드를 사용한 그라디언트 렌더링 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "GradientOverlay.psd";
string outputFile = "output_GradientOverlay.psd";
string outputFilePng = "output_GradientOverlay.png";

var srcMethod = InterpolationMethod.Linear;
var newMethod = InterpolationMethod.Smooth;

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var image = (PsdImage)Image.Load(sourceFile, opt))
{
    // 읽기
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // 변경
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// 저장된 데이터 확인
using (var image = (PsdImage)Image.Load(outputFile, opt))
{
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;

    AssertAreEqual(newMethod, gradientSettings.InterpolationMethod);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### 또 보기

* enum [InterpolationMethod](../../interpolationmethod/)
* class [GradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


