---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Aspose.PSD for .NET API Reference"
description: "VectorShapeOriginSettings プロパティ。このインスタンスが原点ボックスコーナー プロパティを持つかどうかを示す値を取得します"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

このインスタンスが origin box corners プロパティを持つかどうかを示す値を取得します。

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true` このインスタンスが原点ボックスコーナー プロパティを持つ場合; それ以外の場合は `false`。

## 例

以下のコードは、ベクトルパスを含むシェイプレイヤーのサイズ変更機能を示します。

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 関連項目

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


