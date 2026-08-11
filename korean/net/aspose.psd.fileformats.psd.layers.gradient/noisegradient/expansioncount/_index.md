---
title: "NoiseGradient.ExpansionCount"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "NoiseGradient 속성. 확장 횟수를 가져오거나 설정합니다. Photoshop 6.0에서는 2입니다."
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/
---
{{< psd/tize >}}
## NoiseGradient.ExpansionCount property

확장 카운트를 가져오거나 설정합니다 ( = Photoshop 6.0의 경우 2).

```csharp
public short ExpansionCount { get; set; }
```

## 예제

다음 코드는 Gradient map 레이어 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Gradient map 조정 레이어를 추가합니다.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// 저장된 변경 사항 확인
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    var gradientSettings = gradientMapLayer.GradientSettings;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;

    AssertAreEqual((short)4096, solidGradient.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual("Custom", solidGradient.GradientName);
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

* class [NoiseGradient](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../../)


