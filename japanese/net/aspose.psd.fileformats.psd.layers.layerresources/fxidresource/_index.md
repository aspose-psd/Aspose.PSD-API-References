---
title: "クラス FXidResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource クラス。フィルターエフェクトリソースは、スマートフィルター用のチャンネル、ユーザーマスク、シートマスクを含みます。"
type: docs
weight: 2720
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
{{< psd/tize >}}
## FXidResource class

フィルターエフェクトリソースには、チャンネル、ユーザーマスク、スマートフィルタ用のシートマスクが含まれます。

```csharp
public sealed class FXidResource : LayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | `FXidResource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | フィルターエフェクトマスクを取得します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | バージョンを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | タイプツール情報キー FEid。 |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | タイプツール情報キー FXid。 |

## 例

この例は、FXidResource リソースのプロパティを取得および設定する方法を示しています。

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// 保存後に確認してください
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


