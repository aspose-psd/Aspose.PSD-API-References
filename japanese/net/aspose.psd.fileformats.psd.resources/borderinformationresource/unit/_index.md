---
title: BorderInformationResource.Unit
second_title: Aspose.PSD for .NET API リファレンス
description: BorderInformationResource 財産. 境界単位を取得または設定します
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

境界単位を取得または設定します。

```csharp
public PhysicalUnit Unit { get; set; }
```

### 例

次の例は、BorderInformationResource リソースのサポートを示しています。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource を更新します
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### 関連項目

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* 組み立て [Aspose.PSD](../../../)


