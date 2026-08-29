---
title: "Layer.BlendModeKey"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Layer 속성. 블렌드 모드 키를 가져오거나 설정합니다."
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
{{< psd/tize >}}
## Layer.BlendModeKey property

블렌드 모드 키를 가져오거나 설정합니다.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### Property Value

블렌드 모드 키입니다.

## 예제

다음 예제는 Aspose.PSD에서 PassThrough 레이어 혼합 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또 보기

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


