---
title: DataSize
second_title: Aspose.PSD for .NET API 参考
description: 获取资源数据大小以字节为单位
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

获取资源数据大小（以字节为单位）。

```csharp
public override int DataSize { get; }
```

### 适当的价值

资源数据大小。

### 例子

下面的例子演示了对BackgroundColorResource资源的支持。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // 更新 BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### 也可以看看

* class [BackgroundColorResource](../../backgroundcolorresource)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
