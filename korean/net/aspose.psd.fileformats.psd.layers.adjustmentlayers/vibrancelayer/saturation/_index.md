---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "VibranceLayer 속성. 채도를 가져오거나 설정합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

채도를 가져오거나 설정합니다.

```csharp
public int Saturation { get; set; }
```

### Property Value

채도.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | 채도는 -100에서 +100 사이여야 합니다 |

## 예제

다음 코드 예제는 VibranceLayer 레이어 지원과 이 조정을 편집할 수 있는 기능을 보여줍니다.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // 새 VibranceLayer 만들기
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### 또 보기

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


