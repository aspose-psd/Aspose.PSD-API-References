---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD for .NET API 参考
description: BackgroundColorResource 财产. 获取所需的最低 PSD 版本
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

获取所需的最低 PSD 版本。

```csharp
public override int MinimalVersion { get; }
```

### 适当的价值

最小 PSD 版本。

### 例子

以下示例演示了 BackgroundColorResource 资源的支持。

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

* class [BackgroundColorResource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* 部件 [Aspose.PSD](../../../)


