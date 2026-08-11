---
title: "PsdImage.AddGradientMapAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. GradientMap 조정 레이어를 추가합니다"
type: docs
weight: 360
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddGradientMapAdjustmentLayer method

그라디언트 맵 조정 레이어를 추가합니다.

```csharp
public GradientMapLayer AddGradientMapAdjustmentLayer()
```

### 반환 값

GradientMap 인스턴스.

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

* class [GradientMapLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


