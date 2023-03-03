---
title: DropShadowEffect.EffectType
second_title: Aspose.PSD for .NET API リファレンス
description: DropShadowEffect 財産. エフェクトのタイプを取得します
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/
---
## DropShadowEffect.EffectType property

エフェクトのタイプを取得します

```csharp
public LayerEffectsTypes EffectType { get; }
```

### 例

次のコードは、DropShadowEffect の Opacity プロパティの使用を示しています。

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // 不透明度 = 20 の例
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // 不透明度 = 20 の例0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

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
* class [DropShadowEffect](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* 組み立て [Aspose.PSD](../../../)


