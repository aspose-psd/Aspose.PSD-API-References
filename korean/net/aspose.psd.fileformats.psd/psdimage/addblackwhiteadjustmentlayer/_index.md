---
title: "PsdImage.AddBlackWhiteAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. 흑백 조정 레이어를 추가합니다"
type: docs
weight: 300
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddBlackWhiteAdjustmentLayer method

흑백 조정 레이어를 추가합니다.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### 반환 값

생성된 흑백 조정 레이어.

## 예제

다음 예제는 Aspose.PSD에서 런타임에 black white adjustment layer를 추가하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

### 또 보기

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


