---
title: LoadPixels
second_title: Aspose.PSD for .NET API 参考
description: 加载像素
type: docs
weight: 400
url: /zh/net/aspose.psd/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

加载像素。

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 要从中加载像素的矩形。 |

### 返回值

加载的像素数组。

### 例子

这个例子展示了如何在颜色类型的数组中加载像素信息，操作数组并将其设置回图像。为了执行这些操作，此示例使用 MemoryStream 对象创建一个新的图像文件（PSD 格式）。

```csharp
[C#]

//创建一个MemoryStream实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 PsdOptions 的实例并设置其各种属性，包括 Source 属性
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //创建一个Image实例
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //通过指定区域为图像边界来获取图像的像素
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置alrenative索引像素的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //设置索引像素颜色为黄色
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //设置索引像素颜色为蓝色
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //将像素变化应用到图像
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

    //将MemoryStream写入文件
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 也可以看看

* struct [Color](../../color)
* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.PSD](../../rasterimage)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
