---
title: "Image.Create"
second_title: "Aspose.PSD for .NET API 参考"
description: "Image 方法。使用指定的创建选项创建新图像。"
type: docs
weight: 10
url: /zh/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

使用指定的创建选项创建新图像。

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 图像选项。 |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |

### 返回值

新创建的图像。

## 示例

此示例在由 PsdOptions 实例的 Source 属性指定的磁盘位置创建一个新的 Image 文件。在创建实际图像之前，会设置 PsdOptions 实例的多个属性。尤其是指向此案例实际磁盘位置的 Source 属性。

```csharp
[C#]

//创建 PsdOptions 的实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其分配为 PsdOptions 实例的 Source
//第二个布尔参数决定要创建的文件是否为临时文件
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//创建 Image 的实例，并通过调用 Create 方法使用 PsdOptions 实例进行初始化
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //进行一些图像处理。

    // 保存所有更改
    image.Save();
}
```

### 另请参阅

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


