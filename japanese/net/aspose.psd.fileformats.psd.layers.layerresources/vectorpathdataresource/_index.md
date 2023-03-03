---
title: Class VectorPathDataResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource クラス. クラス VectorPathDataResource. このリソースにはベクター レイヤー mask に関する情報が含まれています
type: docs
weight: 3340
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
## VectorPathDataResource class

クラス VectorPathDataResource. このリソースには、ベクター レイヤー mask に関する情報が含まれています。

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | このインスタンスが反転されているかどうかを示す値を取得または設定します. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤ リソース キーを取得します。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | 層リソースの長さをバイト単位で取得します。 |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | パス レコードを取得または設定します。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | psd バージョンを取得します。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | 署名を取得します。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | バージョンを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | 指定したストリーム コンテナーにリソースを保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | を返しますStringこのインスタンスを表す. |

### 例

次の例は、レイヤー ベクター マスク処理のサポートを示しています。パスの編集方法と Aspose.PSD が最終イメージを描画する方法。

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// 読む
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // ベクトル パス ポイントに変更を加える
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

    // エクスポート中
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


