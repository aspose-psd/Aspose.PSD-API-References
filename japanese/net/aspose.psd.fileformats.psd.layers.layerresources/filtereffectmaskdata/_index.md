---
title: Class FilterEffectMaskData
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FilterEffectMaskData クラス. フィルター マスク データ クラス.
type: docs
weight: 2480
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---
## FilterEffectMaskData class

フィルター マスク データ クラス.

```csharp
public sealed class FilterEffectMaskData
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FilterEffectMaskData](filtereffectmaskdata/)(string, Rectangle, int, int, ChannelInformation[], ChannelInformation, Rectangle, ChannelInformation) | の新しいインスタンスを初期化します`FilterEffectMaskData`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Channels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/) { get; } | チャネルを取得します。 |
| [GUID](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/) { get; } | GUID を取得します。 |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/length/) { get; } | フィルター マスク データ長をバイト単位で取得します。 |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maskrectangle/) { get; } | シート マスクの四角形を取得します。 |
| [MaxChannels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maxchannels/) { get; } | チャネル数の最大値を取得します。 |
| [PixelsDepth](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/pixelsdepth/) { get; } | ピクセル深度を取得します。 |
| [Rectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/) { get; } | チャネルの四角形を取得します。 |
| [SheetMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/sheetmask/) { get; } | シート マスクを取得します。 |
| [UserMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/usermask/) { get; } | ユーザーマスクを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SaveData](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/savedata/)(StreamContainer) | 指定したストリーム コンテナーにリソースを保存します。 |

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

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


