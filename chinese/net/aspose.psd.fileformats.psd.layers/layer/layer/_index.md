---
title: "Layer.Layer"
second_title: "Aspose.PSD for .NET API 参考"
description: "Layer 构造函数。初始化 Layer 类的新实例。用于延迟初始化的构造函数"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

初始化 [`Layer`](../) 类的新实例。用于延迟初始化的构造函数。

```csharp
public Layer()
```

## 示例

以下示例演示了在 Aspose.PSD 中使用简易构造函数版本时，如何在新创建的图层上绘图

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // 使用 Pen 工具绘制矩形
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 使用蓝色实心画刷绘制另一个矩形
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

初始化一个新的 [`Layer`](../) 类实例。

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 图像。 |
| disposeImage | 布尔 | 如果设置为 `true` [释放图像]。 |

## 示例

以下代码演示了在不直接加载的情况下，将 JPEG/PNG 等图像文件加载到 PsdImage 的能力。

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### 另请参阅

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

初始化一个新的 [`Layer`](../) 类实例。

```csharp
public Layer(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 图像流 |

## 示例

以下示例演示如何将 Bmp、Jpeg、Jpeg2000、Png、Psd、Tiff、Gif 图像作为图层添加到 PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

从字节数组初始化一个新的 [`Layer`](../) 类实例。

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bounds | Rectangle | 图层边界。 |
| redBytes | Byte[] | 红色字节。 |
| greenBytes | Byte[] | 绿色字节。 |
| blueBytes | Byte[] | 蓝色字节。 |
| name | String | 图层名称。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 字节数组不能为空，或者字节数组长度必须等于边界尺寸 (bounds.Width * bounds.Height) |

### 另请参阅

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


