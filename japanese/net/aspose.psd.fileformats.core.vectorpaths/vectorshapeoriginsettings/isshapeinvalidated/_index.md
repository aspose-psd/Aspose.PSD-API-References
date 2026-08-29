---
title: "VectorShapeOriginSettings.IsShapeInvalidated"
second_title: "Aspose.PSD for .NET API Reference"
description: "VectorShapeOriginSettings プロパティ。形状が無効化されているかどうかを示す値を取得または設定します"
type: docs
weight: 80
url: /ja/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsShapeInvalidated property

shape が無効化されているかどうかを示す値を取得または設定します。

```csharp
public bool IsShapeInvalidated { get; set; }
```

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

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


