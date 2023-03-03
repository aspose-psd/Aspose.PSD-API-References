---
title: FXidResource.FXidResource
second_title: Aspose.PSD for .NET API リファレンス
description: FXidResource コンストラクタ. の新しいインスタンスを初期化しますFXidResourceclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

の新しいインスタンスを初期化します[`FXidResource`](../)class.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| key | Int32 | リソース キー。 |
| version | Int32 | バージョン。 |
| filterEffectMasks | FilterEffectMaskData[] | フィルター効果マスク。 |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* 組み立て [Aspose.PSD](../../../)


