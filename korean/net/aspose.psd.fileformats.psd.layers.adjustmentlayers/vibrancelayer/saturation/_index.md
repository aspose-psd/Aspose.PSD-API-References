---
title: VibranceLayer.Saturation
second_title: .NET API 참조용 Aspose.PSD
description: VibranceLayer 재산. 채도를 가져오거나 설정합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

채도를 가져오거나 설정합니다.

```csharp
public int Saturation { get; set; }
```

### 자산 가치

채도.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | 채도는 -100에서 +100 사이여야 합니다. |

### 예

다음 코드 예제는 VibranceLayer 레이어 지원과 이 조정을 편집하는 기능을 보여줍니다.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // 새로운 VibranceLayer 생성
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### 또한보십시오

* class [VibranceLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* 집회 [Aspose.PSD](../../../)


