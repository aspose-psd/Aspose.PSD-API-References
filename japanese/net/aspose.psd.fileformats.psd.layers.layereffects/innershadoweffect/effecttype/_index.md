---
title: InnerShadowEffect.EffectType
second_title: Aspose.PSD for .NET API リファレンス
description: InnerShadowEffect 財産. エフェクトのタイプを取得します
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/
---
## InnerShadowEffect.EffectType property

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
* class [InnerShadowEffect](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../innershadoweffect/)
* 組み立て [Aspose.PSD](../../../)


