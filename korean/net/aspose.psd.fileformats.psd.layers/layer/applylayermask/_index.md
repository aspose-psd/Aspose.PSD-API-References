---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Layer 메서드. 레이어에 마스크를 적용한 후 마스크를 삭제합니다"
type: docs
weight: 350
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

레이어 마스크를 레이어에 적용한 다음 마스크를 삭제합니다.

```csharp
public void ApplyLayerMask()
```

## 예제

다음 코드는 레이어에 마스크를 적용하는 기능을 보여줍니다.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또 보기

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


