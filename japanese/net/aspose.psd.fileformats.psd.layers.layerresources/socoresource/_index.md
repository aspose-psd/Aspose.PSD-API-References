---
title: Class SoCoResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource クラス. Class SoCoResource. このリソースにはColor Fill Layers に関する情報が含まれています
type: docs
weight: 3010
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Class SoCoResource. このリソースには、Color Fill Layers に関する情報が含まれています。

```csharp
public class SoCoResource : FillLayerResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SoCoResource](socoresource/)() | の新しいインスタンスを初期化します`SoCoResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | RGBカラーを取得します. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | レイヤー リソースに必要な最小限の psd バージョンを取得します。 0 は制限なしを示します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | 層リソース署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | タイプ ツール情報キー。 |

### 例

次の例は、SoCoResource (塗りつぶしレイヤーのレイヤー リソース) を編集する方法を示しています。

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// 既存の画像を PsdImage クラスのインスタンスにロードします
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // FillLayer の検索
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // レイヤ リソース リストでの SoCoResource の検索
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // SoCoResource Color プロパティを設定する
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


