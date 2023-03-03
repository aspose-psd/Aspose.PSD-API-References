---
title: Class VsmsResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VsmsResource クラス. クラス VsmsResource. このリソースにはベクター レイヤー mask に関する情報が含まれています
type: docs
weight: 3380
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---
## VsmsResource class

クラス VsmsResource. このリソースには、ベクター レイヤー mask に関する情報が含まれています。

```csharp
public class VsmsResource : VectorPathDataResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [VsmsResource](vsmsresource/#constructor)() | の新しいインスタンスを初期化します`VsmsResource`class. |
| [VsmsResource](vsmsresource/#constructor_1)(byte[]) | の新しいインスタンスを初期化します`VsmsResource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | このインスタンスが反転されているかどうかを示す値を取得または設定します. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/key/) { get; } | レイヤ リソース キーを取得します。 |
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

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/typetoolkey/) | タイプ ツール情報キー。 |

### 例

次の例は、VsmsResource リソースの読み込みのサポートを示しています。パスの編集方法。

```csharp
[C#]

[Test]
public void TestPsdNet140()
{
    // VsmsResource のサポート
    string sourceFileName = "EmptyRectangle.psd";
    string exportPath = "EmptyRectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVsmsResource(im);
        // 読む
        if (resource.IsDisabled != false ||
            resource.IsInverted != false ||
            resource.IsNotLinked != false ||
            resource.Paths.Length != 7 ||
            resource.Paths[0].Type != VectorPathType.PathFillRuleRecord ||
            resource.Paths[1].Type != VectorPathType.InitialFillRuleRecord ||
            resource.Paths[2].Type != VectorPathType.ClosedSubpathLengthRecord ||
            resource.Paths[3].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[4].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[5].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[6].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked)
        {
            throw new Exception("VsmsResource was read wrong");
        }

        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];

        // パス塗りつぶしルールには追加情報は含まれていません
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // 編集中
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039798, 10905191);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VsmsResource GetVsmsResource(PsdImage image)
{
    var layer = image.Layers[1];
    VsmsResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VsmsResource)
        {
            resource = (VsmsResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VsmsResource not found");
    }
    return resource;
}
```

### 関連項目

* class [VectorPathDataResource](../vectorpathdataresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


