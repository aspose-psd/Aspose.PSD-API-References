---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: Aspose.PSD for .NET API リファレンス
description: VectorShapeOriginSettings 財産. このインスタンスが変換プロパティを持っているかどうかを示す値を取得します.
type: docs
weight: 100
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

このインスタンスが変換プロパティを持っているかどうかを示す値を取得します.

```csharp
public bool IsTransformPresent { get; }
```

### プロパティ値

`真実`このインスタンスに変換プロパティがある場合。さもないと、`間違い` .

### 例

次のコードは、ベクター パスを含むシェイプ レイヤーのサイズを変更する機能を示しています。

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
* 名前空間 [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* 組み立て [Aspose.PSD](../../../)


