---
title: RasterImage.SavePixels
second_title: Aspose.PSD for .NET API 参考
description: RasterImage 方法. 保存像素
type: docs
weight: 520
url: /zh/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

保存像素。

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 要将像素保存到的矩形。 |
| pixels | Color[] | 像素数组。 |

### 例子

此示例显示如何加载类型颜色数组中的像素信息、操作数组并将其设置回图像。为执行这些操作，此示例使用 MemoryStream 对象创建了一个新的图像文件（PSD 格式）。

```csharp
[C#]

//创建一个内存流实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 PsdOptions 的实例并设置其各种属性，包括 Source 属性
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //创建图像实例
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //通过指定区域作为图像边界获取图像的像素
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置替代索引像素的颜色
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

        //将像素变化应用于图像
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

    //将内存流写入文件
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 也可以看看

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* 命名空间 [Aspose.PSD](../../rasterimage/)
* 部件 [Aspose.PSD](../../../)


