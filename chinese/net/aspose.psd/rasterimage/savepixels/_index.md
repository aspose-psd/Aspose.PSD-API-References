---
title: "RasterImage.SavePixels"
second_title: "Aspose.PSD for .NET API 参考"
description: "RasterImage 方法。保存像素"
type: docs
weight: 540
url: /zh/net/aspose.psd/rasterimage/savepixels/
---
{{< psd/tize >}}
## RasterImage.SavePixels method

保存像素。

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 用于保存像素的矩形。 |
| 像素 | Color[] | 像素数组。 |

## 示例

此示例展示如何将像素信息加载到 Color 类型的数组中，操作该数组并将其设置回图像。为执行这些操作，示例使用 MemoryStream 对象创建一个新的 Image 文件（PSD 格式）。

```csharp
[C#]

//创建 MemoryStream 的实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 PsdOptions 的实例并设置其各种属性，包括 Source 属性
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //通过将区域指定为图像边界来获取图像的像素
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //循环遍历数组并设置交替索引像素的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //将索引像素的颜色设置为黄色
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //将索引像素的颜色设置为蓝色
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //将像素更改应用于图像
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

    //将 MemoryStream 写入文件
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 另请参阅

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


