---
title: "クラス VsmsResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VsmsResource クラス。クラス VsmsResource。このリソースはベクターレイヤーマスクに関する情報を含みます。"
type: docs
weight: 3780
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---
{{< psd/tize >}}
## VsmsResource class

VsmsResource クラス。このリソースはベクトルレイヤーマスクに関する情報を含みます。

```csharp
public class VsmsResource : VectorPathDataResource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [VsmsResource](vsmsresource/#constructor)() | 新しい `VsmsResource` クラスのインスタンスを初期化します。 |
| [VsmsResource](vsmsresource/#constructor_1)(byte[]) | 新しい `VsmsResource` クラスのインスタンスを初期化します。 |

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

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/typetoolkey/) | タイプツール情報キーです。 |

## 例

次の例は VsmsResource のリソース読み込みのサポートを示します。パスの編集がどのように機能するかを説明します。

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
        // 読み取り
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

        // パスの塗りルールには追加情報が含まれていません
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // 編集
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


