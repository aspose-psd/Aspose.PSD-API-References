---
title: StreamSource.StreamSource
second_title: Aspose.PSD for .NET API 参考
description: StreamSource 构造函数. 初始化一个新的实例StreamSource类.
type: docs
weight: 10
url: /zh/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

初始化一个新的实例[`StreamSource`](../)类.

```csharp
public StreamSource(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要打开的流。 |

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

* class [StreamSource](../)
* 命名空间 [Aspose.PSD.Sources](../../streamsource/)
* 部件 [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

初始化一个新的实例[`StreamSource`](../)类.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要打开的流。 |
| disposeStream | Boolean | 如果设置为`真的`流将被处理。 |

### 例子

这个例子演示了使用 System.IO.Stream 来创建一个新的图像文件

```csharp
[C#]

//创建 PsdOptions 的实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建System.IO.Stream的实例
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//定义PsdOptions实例的source属性
//第二个布尔参数决定流一旦超出范围是否被释放
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//创建一个Image实例，调用Create方法以PsdOptions为参数初始化Image对象   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //做一些图像处理
}
```

### 也可以看看

* class [StreamSource](../)
* 命名空间 [Aspose.PSD.Sources](../../streamsource/)
* 部件 [Aspose.PSD](../../../)


