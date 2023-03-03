---
title: Class VibAResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VibAResource クラス. VibA リソース.
type: docs
weight: 3350
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---
## VibAResource class

VibA リソース.

```csharp
public class VibAResource : AdjustmentLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [VibAResource](vibaresource/)() | の新しいインスタンスを初期化します`VibAResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/) { get; } | レイヤー リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/) { get; } | psd バージョンを取得します。 |
| [Saturation](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/) { get; set; } | 彩度値を取得または設定します |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 署名を取得します。 |
| [Vibrance](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/) { get; set; } | バイブランス値を取得または設定します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/) | タイプ ツール情報キー。 |

### 例

次のコード例は、VibAResource リソースのサポートを示しています。

```csharp
[C#]

// 実行時のバイブレーション リソースの読み取りと書き込みのサポートの例。
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### 関連項目

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


