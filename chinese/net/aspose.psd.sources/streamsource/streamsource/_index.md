---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD for .NET API 参考"
description: "StreamSource 构造函数。初始化 StreamSource 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

初始化 [`StreamSource`](../) 类的新实例。

```csharp
public StreamSource(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 要打开的流。 |

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

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

初始化 [`StreamSource`](../) 类的新实例。

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 要打开的流。 |
| disposeStream | 布尔 | 如果设置为 `true`，流将被释放。 |

## 示例

此示例演示了使用 System.IO.Stream 创建新 Image 文件。

```csharp
[C#]

//创建 PsdOptions 的实例并设置其各项属性。
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 System.IO.Stream 的实例。
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//为 PsdOptions 实例定义 source 属性。
//第二个布尔参数决定在超出作用域后是否释放 Stream。
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//创建 Image 的实例，并使用 PsdOptions 作为参数调用 Create 方法以初始化 Image 对象。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //进行一些图像处理。
}
```

### 另请参阅

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


