---
title: ILayerEffect.EffectType
second_title: Aspose.PSD for .NET API リファレンス
description: ILayerEffect 財産. エフェクトのタイプを取得します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
## ILayerEffect.EffectType property

エフェクトのタイプを取得します

```csharp
public LayerEffectsTypes EffectType { get; }
```

### 例

次のコードは、ILayerEffect.EffectType プロパティのサポートを示しています。

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // キャッチした
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 関連項目

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* interface [ILayerEffect](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../ilayereffect/)
* 組み立て [Aspose.PSD](../../../)


