---
title: "BlendingOptions.AreEffectsEnabled"
second_title: "Aspose.PSD for .NET API Reference"
description: "BlendingOptions プロパティ。すべてのレイヤー効果の可視性を取得または設定します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/
---
{{< psd/tize >}}
## BlendingOptions.AreEffectsEnabled property

すべてのレイヤー効果の可視性を取得または設定します。

```csharp
public bool AreEffectsEnabled { get; set; }
```

## 例

AreEffectsEnabled プロパティを使用してレイヤー効果を有効または無効にする方法を示します。

```csharp
[C#]

string srcFile = "2485.psd";
string outputOnFile = "on_2485.png";
string outputOffFile = "off_2485.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Save(outputOnFile);

    psdImage.Layers[1].BlendingOptions.AreEffectsEnabled = false;

    psdImage.Save(outputOffFile);
}
```

### 関連項目

* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


