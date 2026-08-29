---
title: "クラス VectorShapeOriginSettings"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings クラス。ベクトルシェイプの起点設定"
type: docs
weight: 1450
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

ベクトル形状の起点設定。

```csharp
public sealed class VectorShapeOriginSettings
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | `VectorShapeOriginSettings` クラスの新しいインスタンスを初期化します。 |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | `VectorShapeOriginSettings` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | このインスタンスが origin box corners プロパティを持つかどうかを示す値を取得します。 |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | このインスタンスが origin index プロパティを持つかどうかを示す値を取得します。 |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | このインスタンスが origin radii rectangle プロパティを持つかどうかを示す値を取得します。 |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | このインスタンスが origin resolution プロパティを持つかどうかを示す値を取得します。 |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | このインスタンスが rectangle プロパティを持つかどうかを示す値を取得します。 |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | このインスタンスが origin type プロパティを持つかどうかを示す値を取得します。 |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | shape が無効化されているかどうかを示す値を取得または設定します。 |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | このインスタンスが shape invalidated プロパティを設定しているかどうかを示す値を取得します。 |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | このインスタンスが transform プロパティを持つかどうかを示す値を取得します。 |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | origin box のコーナーを取得または設定します。 |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | origin shape のインデックスを取得または設定します。 |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | origin radii rectangle を取得または設定します。 |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | origin resolution を取得または設定します。 |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | origin shape bounding box を取得または設定します。 |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | origin のタイプを取得または設定します。 |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | 変換行列を取得または設定します。 |

## 例

次の例は VogkResource リソースのサポートを示しています。

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // 読み取り
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // 編集
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


