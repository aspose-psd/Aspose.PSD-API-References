---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. 반전 조정 레이어를 추가합니다."
type: docs
weight: 380
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

반전 조정 레이어를 추가합니다.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### 반환 값

생성된 반전 레이어

## 예제

다음 코드는 InvertAdjustmentLayer에 대한 지원과 InvertAdjustmentLayer를 추가하는 방법을 보여줍니다.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### 또 보기

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


