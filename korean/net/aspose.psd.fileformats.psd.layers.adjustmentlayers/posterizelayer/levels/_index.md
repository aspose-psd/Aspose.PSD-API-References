---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PosterizeLayer 속성. 포스터화 레이어의 레벨"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

Posterize 레이어의 레벨.

```csharp
public short Levels { get; set; }
```

## 예제

다음 코드는 PosterizeLayer의 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    foreach (Layer layer in image.Layers)
    {
        if (layer is PosterizeLayer)
        {
            ((PosterizeLayer)layer).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### 또 보기

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


