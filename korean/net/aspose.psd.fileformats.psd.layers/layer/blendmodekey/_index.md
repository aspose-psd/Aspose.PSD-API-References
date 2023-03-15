---
title: Layer.BlendModeKey
second_title: .NET API 참조용 Aspose.PSD
description: Layer 재산. 혼합 모드 키를 가져오거나 설정합니다.
type: docs
weight: 40
url: /ko/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
## Layer.BlendModeKey property

혼합 모드 키를 가져오거나 설정합니다.

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### 자산 가치

혼합 모드 키입니다.

### 예

다음 예는 Aspose.PSD에서 PassThrough 레이어 혼합 모드를 사용하는 방법을 보여줍니다.

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

### 또한보십시오

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 집회 [Aspose.PSD](../../../)


