---
title: "クラス VectorPathDataResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource クラス。 クラス VectorPathDataResource。 このリソースはベクターレイヤーマスクに関する情報を含みます。"
type: docs
weight: 3740
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
{{< psd/tize >}}
## VectorPathDataResource class

VectorPathDataResource クラス。このリソースはベクトルレイヤーマスクに関する情報を含みます。

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | このインスタンスが反転しているかどうかを示す値を取得または設定します。 |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | パス レコードを取得または設定します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | バージョンを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## 例

次の例はレイヤーベクトルマスク処理のサポートを示しています。 パスの編集がどのように機能し、Aspose.PSD が最終画像を描画する方法です。

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// 読み取り
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // ベクトルパスのポイントを変更します
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // エクスポート
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


