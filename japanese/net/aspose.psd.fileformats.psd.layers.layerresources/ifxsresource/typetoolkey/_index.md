---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD for .NET API Reference"
description: "IfxsResource フィールド。タイプツール情報キーです"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

タイプツール情報キーです。

```csharp
public const int TypeToolKey;
```

## 例

次のコードは IfxsResource のサポートを示しています。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // 例ではエフェクト付きのグループレイヤーが 2 つあります
    // エフェクトが 1 つのグループレイヤー
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // エフェクトが多数あるグループレイヤー
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // エフェクトの数を取得し、その数量を検証します
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // グループレイヤー内の 1 つのエフェクトはリソース 'IfxsResource' にあります
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // グループレイヤー内の 2 つ以上のエフェクトはリソース 'ImfxResource' にあります
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // 複数のエフェクトがあるグループレイヤーに3番目のシャドウを追加する
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### 関連項目

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


