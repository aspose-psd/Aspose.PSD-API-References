---
title: "クラス IfxsResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource クラス。Ifxs リソース グループレイヤーエフェクトリソース"
type: docs
weight: 2840
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ifxs リソース（グループレイヤーエフェクトリソース）

```csharp
public sealed class IfxsResource : BaseFxResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [IfxsResource](ifxsresource/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | ディスクリプタのバージョンを取得します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | タイプツール情報キーです。 |

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

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


