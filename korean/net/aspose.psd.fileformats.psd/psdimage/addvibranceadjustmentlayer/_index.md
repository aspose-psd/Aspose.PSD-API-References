---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: .NET API 참조용 Aspose.PSD
description: PsdImage 방법. 생동감 조정 레이어를 추가합니다.
type: docs
weight: 430
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

생동감 조정 레이어를 추가합니다.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### 반환 값

새로 생성된 Vibrance 레이어.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)


