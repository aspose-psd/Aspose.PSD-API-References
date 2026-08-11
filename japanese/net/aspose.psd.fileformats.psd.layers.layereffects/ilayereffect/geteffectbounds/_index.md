---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD for .NET API Reference"
description: "ILayerEffect メソッド。入力レイヤーのピクセル境界に基づいて効果ピクセルの境界を計算し、取得します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layerBounds | Rectangle | レイヤーのピクセル境界です。 |
| globalAngle | Int32 | グローバル光角度を計算するためのグローバル角度です。 |

### 戻り値

入力レイヤーのピクセル境界に基づく効果ピクセルの境界です。

## 例

エフェクト付きレイヤーの境界を取得し、正しいサイズでエクスポートする方法を示します。

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
                                                // `boundsToExport = psdImage.Bounds; // 元のレイヤー位置で PsdImage の境界内に保存するため`

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

### 関連項目

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


