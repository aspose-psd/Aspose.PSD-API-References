---
title: "BorderInformationResource.Width"
second_title: "Aspose.PSD for .NET API Reference"
description: "BorderInformationResource プロパティ。ボーダーの幅を取得または設定します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
{{< psd/tize >}}
## BorderInformationResource.Width property

境界幅を取得または設定します。

```csharp
public double Width { get; set; }
```

## 例

次の例は BorderInformationResource リソースのサポートを示しています。

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

    // BorderInformationResource を更新する
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### 関連項目

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


