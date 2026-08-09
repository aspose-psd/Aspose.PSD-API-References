---
title: "ClassID.ClassID"
second_title: "Aspose.PSD for .NET API 参考"
description: "ClassID 构造函数。初始化 ClassID 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
{{< psd/tize >}}
## ClassID(byte[]) {#constructor}

初始化 [`ClassID`](../) 类的新实例。

```csharp
public ClassID(byte[] classID)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classID | Byte[] | 类 ID 作为一系列字节。 |

### 另请参阅

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

初始化 [`ClassID`](../) 类的新实例。

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classID | Byte[] | 类 ID 作为一系列字节。 |
| isZeroLength | 布尔 | 如果设置为 `true` [长度为零]。记录的字符串长度为零，但实际为四。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | classID 为 null。 |

### 另请参阅

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

初始化 [`ClassID`](../) 类的新实例。

```csharp
public ClassID(int classID)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classID | Int32 | 类标识。 |

### 另请参阅

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

初始化 [`ClassID`](../) 类的新实例。

```csharp
public ClassID(uint classID)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classID | UInt32 | 类标识。 |

### 另请参阅

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

初始化 [`ClassID`](../) 类的新实例。

```csharp
public ClassID(string classID, bool isZeroLength)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classID | String | class ID 在 ASCII 编码中。 |
| isZeroLength | 布尔 | 如果设置为 `true` [长度为零]。 |

## 示例

此示例演示，从图像导入的图层被转换为 smart object layer，并且保存的 PSD 文件是正确的。

```csharp
[C#]

// 测试图层从图像导入后被转换为 smart object layer，并且保存的 PSD 文件是正确的。

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
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

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 另请参阅

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

初始化 [`ClassID`](../) 类的新实例。

```csharp
public ClassID(string classID)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| classID | String | class ID 在 ASCII 编码中。 |

### 另请参阅

* class [ClassID](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


