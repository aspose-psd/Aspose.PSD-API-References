---
title: BorderInformationResource.MinimalVersion
second_title: Aspose.PSD for .NET API 参考
description: BorderInformationResource 财产. 获取所需的最低 PSD 版本
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

获取所需的最低 PSD 版本。

```csharp
public override int MinimalVersion { get; }
```

### 适当的价值

最小 PSD 版本。

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


