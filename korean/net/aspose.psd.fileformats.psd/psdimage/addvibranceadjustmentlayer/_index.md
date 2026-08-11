---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. Vibrance 조정 레이어를 추가합니다"
type: docs
weight: 490
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

비브런스 조정 레이어를 추가합니다.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### 반환 값

새로 만든 Vibrance 레이어입니다.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


