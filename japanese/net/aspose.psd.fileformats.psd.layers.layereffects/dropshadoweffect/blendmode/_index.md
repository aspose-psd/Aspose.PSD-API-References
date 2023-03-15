---
title: DropShadowEffect.BlendMode
second_title: Aspose.PSD for .NET API リファレンス
description: DropShadowEffect 財産. ブレンド モードを取得または設定します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/
---
## DropShadowEffect.BlendMode property

ブレンド モードを取得または設定します。

```csharp
public BlendMode BlendMode { get; set; }
```

### プロパティ値

ブレンドモード.

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

### 関連項目

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [DropShadowEffect](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* 組み立て [Aspose.PSD](../../../)


