---
title: Class FXidResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource クラス. Filter Effects リソースにはスマート フィルター用のチャネルユーザー マスクおよびシート マスクが含まれています
type: docs
weight: 2460
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
## FXidResource class

Filter Effects リソースには、スマート フィルター用のチャネル、ユーザー マスク、およびシート マスクが含まれています。

```csharp
public sealed class FXidResource : LayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | の新しいインスタンスを初期化します`FXidResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | フィルター効果マスクを取得します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/psdversion/) { get; } | レイヤー リソースに必要な最小限の psd バージョンを取得します。 0 は制限なしを示します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/signature/) { get; } | 層リソース署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | バージョンを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | タイプ ツール情報キー FEid. |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | タイプ ツール情報キー FXid. |

### 例

この例では、FXidResource リソースのプロパティを取得および設定する方法を示します。

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

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

// 保存後にチェック
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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


