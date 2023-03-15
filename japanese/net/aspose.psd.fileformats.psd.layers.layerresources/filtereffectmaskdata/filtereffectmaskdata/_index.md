---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD for .NET API リファレンス
description: FilterEffectMaskData コンストラクタ. の新しいインスタンスを初期化しますFilterEffectMaskDataclass.
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

の新しいインスタンスを初期化します[`FilterEffectMaskData`](../)class.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| guid | String | リソース GUID。 |
| rectangle | Rectangle | チャネルの長方形。 |
| pixelsDepth | Int32 | ピクセル深度。 |
| maxChannels | Int32 | 最大チャネル値。 |
| channels | ChannelInformation[] | チャネル。 |
| userMask | ChannelInformation | ユーザーマスク。 |
| maskRectangle | Rectangle | シート マスクの四角形。 |
| sheetMask | ChannelInformation | シートマスクです。 |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* 組み立て [Aspose.PSD](../../../)


