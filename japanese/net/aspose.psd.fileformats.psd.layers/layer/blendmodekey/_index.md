---
title: Layer.BlendModeKey
second_title: Aspose.PSD for .NET API リファレンス
description: Layer 財産. ブレンド モード キーを取得または設定します
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers/layer/blendmodekey/
---
## Layer.BlendModeKey property

ブレンド モード キーを取得または設定します。

```csharp
public virtual BlendMode BlendModeKey { get; set; }
```

### プロパティ値

ブレンドモードキー.

### 例

次の例は、Aspose.PSD で PassThrough レイヤー ブレンド モードを使用する方法を示しています。

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

### 関連項目

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [Layer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 組み立て [Aspose.PSD](../../../)


