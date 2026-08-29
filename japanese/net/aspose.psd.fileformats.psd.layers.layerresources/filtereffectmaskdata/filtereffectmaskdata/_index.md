---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD for .NET API Reference"
description: "FilterEffectMaskData コンストラクタ。FilterEffectMaskData クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

[`FilterEffectMaskData`](../) クラスの新しいインスタンスを初期化します。

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | 文字列 | リソース GUIDです。 |
| 矩形 | Rectangle | チャンネル矩形です。 |
| pixelsDepth | Int32 | ピクセル深度です。 |
| maxChannels | Int32 | 最大チャンネル数の値です。 |
| channels | ChannelInformation[] | チャンネル。 |
| userMask | ChannelInformation | ユーザーマスク。 |
| maskRectangle | Rectangle | シートマスクの矩形。 |
| sheetMask | ChannelInformation | シートマスク。 |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


