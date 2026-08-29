---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ILayerEffect 메서드. 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다"
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerBounds | Rectangle | 레이어 픽셀 경계. |
| globalAngle | Int32 | 전역 조명 각도를 계산하기 위한 전역 각도. |

### 반환 값

입력 레이어 픽셀 경계를 기반으로 한 효과 픽셀의 경계.

## 예제

효과가 적용된 레이어의 경계를 가져오고 올바른 크기로 내보내는 방법을 보여줍니다.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // 원래 레이어 위치에서 PsdImage 경계 내에 저장하기 위해

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### 또 보기

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


