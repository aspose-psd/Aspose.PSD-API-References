---
title: VogkResource.Key
second_title: Aspose.PSD for .NET API リファレンス
description: VogkResource 財産. レイヤ リソース キーを取得します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/
---
## VogkResource.Key property

レイヤ リソース キーを取得します。

```csharp
public override int Key { get; }
```

### 例

次の例は、VogkResource リソースのサポートを示しています。

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

    // 読む
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // 編集中
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### 関連項目

* class [VogkResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* 組み立て [Aspose.PSD](../../../)


