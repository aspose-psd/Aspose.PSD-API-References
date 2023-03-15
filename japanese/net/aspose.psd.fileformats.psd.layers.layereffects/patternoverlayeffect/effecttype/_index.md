---
title: PatternOverlayEffect.EffectType
second_title: Aspose.PSD for .NET API リファレンス
description: PatternOverlayEffect 財産. エフェクトの種類を取得 type
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/
---
## PatternOverlayEffect.EffectType property

エフェクトの種類を取得 type

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
* class [PatternOverlayEffect](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../patternoverlayeffect/)
* 組み立て [Aspose.PSD](../../../)


