---
title: "클래스 SolidGradient"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Gradient.SolidGradient 클래스. 그라디언트 채우기 효과 설정"
type: docs
weight: 2230
url: /ko/net/aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---
{{< psd/tize >}}
## SolidGradient class

그라디언트 채우기 효과 설정입니다.

```csharp
public class SolidGradient : BaseGradient
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SolidGradient](solidgradient/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/colorpoints/) { get; set; } | 색상 포인트를 가져오거나 설정합니다. |
| override [GradientMode](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/gradientmode/) { get; } | 이 그라디언트의 모드를 가져옵니다. 'Gradient Type' = 'Solid/Noise' (0/1) 를 결정합니다. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.gradient/basegradient/gradientname/) { get; set; } | 그라디언트의 이름을 가져오거나 설정합니다. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/interpolation/) { get; set; } | 보간을 가져오거나 설정합니다. 'Gradient Type'이 'Solid'일 때 부드러움을 결정합니다. 값 범위: 0-4096. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/transparencypoints/) { get; set; } | 투명도 포인트를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addcolorpoint/)() | 색상 포인트를 추가합니다. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/addtransparencypoint/)() | 색상 포인트를 추가합니다. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removecolorpoint/)(IGradientColorPoint) | 색상 포인트를 제거합니다. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/removetransparencypoint/)(IGradientTransparencyPoint) | 투명도 포인트를 제거합니다. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.gradient/solidgradient/generatelfx2resourcenodes/)() | LFX2 리소스 노드를 생성합니다. |

## 예제

스트로크 채우기 효과에서 노이즈 및 솔리드 그라디언트 설정을 읽고 수정하는 방법을 보여줍니다.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // 공통 그라디언트 채우기 설정 속성 확인
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // 노이즈 그라디언트 속성 확인
    NoiseGradient noiseGradient = gradientFillSettings.Gradient as NoiseGradient;
    AssertIsNotNull(noiseGradient);
    AssertAreEqual(GradientKind.Noise, noiseGradient.GradientMode);
    AssertAreEqual(2107422935, noiseGradient.RndNumberSeed);
    AssertAreEqual(false, noiseGradient.ShowTransparency);
    AssertAreEqual(false, noiseGradient.UseVectorColor);
    AssertAreEqual(2048, noiseGradient.Roughness);
    AssertAreEqual(NoiseColorModel.RGB, noiseGradient.ColorModel);
    AssertAreEqual((long)0, noiseGradient.MinimumColor.GetAsLong());
    AssertAreEqual(28147819798528050, noiseGradient.MaximumColor.GetAsLong());

    // 그라디언트 설정 변경
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Dither = false;
    gradientFillSettings.Reverse = false;
    gradientFillSettings.Angle = 30;
    gradientFillSettings.Scale = 80;
    gradientFillSettings.GradientType = GradientType.Linear;

    var solidGradient = new SolidGradient();
    solidGradient.Interpolation = 2048;
    solidGradient.ColorPoints[0].RawColor.Components[0].Value = 255; // A
    solidGradient.ColorPoints[0].RawColor.Components[1].Value = 255; // R 
    solidGradient.ColorPoints[0].RawColor.Components[2].Value = 0;   // G
    solidGradient.ColorPoints[0].RawColor.Components[3].Value = 0;   // B
    solidGradient.TransparencyPoints[1].Opacity = 50;
    gradientFillSettings.Gradient = solidGradient;

    image.Save(outputFile);
}

// 저장된 변경 사항 확인
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // 공통 그라디언트 채우기 설정 속성 확인
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(false, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(false, gradientFillSettings.Dither);
    AssertAreEqual(false, gradientFillSettings.Reverse);
    AssertAreEqual(30.0, gradientFillSettings.Angle);
    AssertAreEqual(80, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Linear, gradientFillSettings.GradientType);

    SolidGradient solidGradient = gradientFillSettings.Gradient as SolidGradient;
    AssertIsNotNull(solidGradient);
    AssertAreEqual((short)2048, solidGradient.Interpolation);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[0].Value);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[1].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[2].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[3].Value);
    AssertAreEqual(50.0, solidGradient.TransparencyPoints[1].Opacity);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### 또 보기

* class [BaseGradient](../basegradient/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../)


