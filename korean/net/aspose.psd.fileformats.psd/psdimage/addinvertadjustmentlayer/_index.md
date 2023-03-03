---
title: PsdImage.AddInvertAdjustmentLayer
second_title: .NET API 참조용 Aspose.PSD
description: PsdImage 방법. 반전 조정 레이어를 추가합니다.
type: docs
weight: 360
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

반전 조정 레이어를 추가합니다.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### 반환 값

생성된 반전 레이어

### 예

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

### 또한보십시오

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 집회 [Aspose.PSD](../../../)


