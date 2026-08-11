---
title: "열거형 InterpolationMethod"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod 열거형. Photoshop 그라디언트 보간 방법을 위한 패킹된 fourCC 값. 디스크립터 키 gradientsInterpolationMethod"
type: docs
weight: 2160
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Photoshop 그라디언트 보간 방법을 위한 패킹된 fourCC 값. 디스크립터 키: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — 클래식 (키가 없을 때의 레거시 기본값). |
| Perceptual | `1348825699` | 'Perc' — 퍼셉추얼. |
| Linear | `1282306592` | 'Lnr ' — 선형 (뒤에 공백이 있음). |
| Smooth | `1399680879` | 'Smoo' — 스무스. |
| Stripes | `1195986291` | 'GIMs' — 스트라이프. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


