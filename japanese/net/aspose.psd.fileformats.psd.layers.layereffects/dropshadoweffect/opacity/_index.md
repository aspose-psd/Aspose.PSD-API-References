---
title: "DropShadowEffect.Opacity"
second_title: "Aspose.PSD for .NET API Reference"
description: "DropShadowEffect プロパティ。不透明度を取得または設定します"
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/
---
{{< psd/tize >}}
## DropShadowEffect.Opacity property

不透明度を取得または設定します。

```csharp
public byte Opacity { get; set; }
```

### Property Value

不透明度です。

## 例

以下のコードは、DropShadowEffect の Opacity プロパティの使用例を示しています。

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

    // Opacity = 20 の例
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Opacity = 200 の例
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### 関連項目

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


