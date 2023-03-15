---
title: Image.Create
second_title: Aspose.PSD for .NET API 参考
description: Image 方法. 使用指定的创建选项创建新图像
type: docs
weight: 10
url: /zh/net/aspose.psd/image/create/
---
## Image.Create method

使用指定的创建选项创建新图像。

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 图像选项。 |
| width | Int32 | 宽度. |
| height | Int32 | 高度. |

### 返回值

新创建的图像。

### 例子

此示例在 PsdOptions 实例的 Source 属性指定的某个磁盘位置创建一个新的图像文件。在创建实际图像之前设置 PsdOptions 实例的几个属性。特别是 Source 属性，在这种情况下指的是实际磁盘位置。

```csharp
[C#]

//创建 PsdOptions 实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其指定为 PsdOptions 实例的源
//第二个布尔参数确定要创建的文件是否为IsTemporal
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//创建Image的实例并通过调用Create方法用PsdOptions的实例初始化它
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //做一些图像处理

    // 保存所有更改
    image.Save();
}
```

### 也可以看看

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* 命名空间 [Aspose.PSD](../../image/)
* 部件 [Aspose.PSD](../../../)


