---
title: BorderInformationResource.Width
second_title: Aspose.PSD for .NET API 参考
description: BorderInformationResource 财产. 获取或设置边框宽度
type: docs
weight: 50
url: /zh/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
## BorderInformationResource.Width property

获取或设置边框宽度。

```csharp
public double Width { get; set; }
```

### 例子

以下示例演示了 BorderInformationResource 资源的支持。

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

    // 更新 BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### 也可以看看

* class [BorderInformationResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* 部件 [Aspose.PSD](../../../)


