---
title: "PsdImage.AddPosterizeAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdImage 메서드. 포스터라이즈 조정 레이어를 추가합니다"
type: docs
weight: 430
url: /ko/net/aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddPosterizeAdjustmentLayer method

포스터라이즈 조정 레이어를 추가합니다.

```csharp
public PosterizeLayer AddPosterizeAdjustmentLayer()
```

### 반환 값

PosterizeLayer 인스턴스.

## 예제

다음 코드는 PsdImage를 통해 PosterizeAdjustmentLayer를 추가하는 기능을 보여줍니다.

```csharp
[C#]

string srcFile = "zendeya.psd";
string outFile = "zendeya.psd.out.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    psdImage.AddPosterizeAdjustmentLayer();
    psdImage.Save(outFile);
}

// 저장된 변경 사항 확인
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    AssertAreEqual(2, image.Layers.Length);

    PosterizeLayer posterizeLayer = (PosterizeLayer)image.Layers[1];

    AssertAreEqual(true, posterizeLayer is PosterizeLayer);
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

* class [PosterizeLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


