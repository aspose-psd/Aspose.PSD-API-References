---
title: Class BezierKnotRecord
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Core.VectorPaths.BezierKnotRecord クラス. ベジエ ノット レコード Class
type: docs
weight: 1330
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/
---
## BezierKnotRecord class

ベジエ ノット レコード Class

```csharp
public class BezierKnotRecord : VectorPathRecord
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BezierKnotRecord](bezierknotrecord/#constructor)() | の新しいインスタンスを初期化します`BezierKnotRecord`class. |
| [BezierKnotRecord](bezierknotrecord/#constructor_1)(byte[]) | の新しいインスタンスを初期化します`BezierKnotRecord`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/isclosed/) { get; set; } | このインスタンスが閉じているかどうかを示す値を取得または設定します。 |
| [IsLinked](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/islinked/) { get; set; } | このインスタンスがリンクされているかどうかを示す値を取得または設定します。 |
| [IsOpen](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/isopen/) { get; set; } | このインスタンスが開いているかどうかを示す値を取得または設定します。 |
| [PathPoints](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/pathpoints/) { get; set; } | パス ポイントを取得または設定します。 |
| [Points](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/points/) { get; set; } | ポイントを取得または設定します。 |
| override [Type](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/type/) { get; } | 型を取得します. |

### 例

次の例は、VmskResource リソースの読み込みのサポートを示しています。パスの編集方法。

```csharp
[C#]

[Test]
public void TestPsdNet106()
{
    string sourceFileName = "Rectangle.psd";
    string exportPath = "Rectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVmskResource(im);
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
            throw new Exception("VmskResource was read wrong");
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
            throw new Exception("VmskResource paths were read wrong");
        }
        // 編集中
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039797, 10905190);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VmskResource GetVmskResource(PsdImage image)
{
    var layer = image.Layers[1];
    VmskResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VmskResource)
        {
            resource = (VmskResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VmskResource not found");
    }
    return resource;
}
```

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

* class [VectorPathRecord](../vectorpathrecord/)
* 名前空間 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* 組み立て [Aspose.PSD](../../)


