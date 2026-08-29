---
title: "Image.RotateFlip"
second_title: "Aspose.PSD for .NET API 参考"
description: "Image 方法。旋转、翻转或同时旋转和翻转图像"
type: docs
weight: 230
url: /zh/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

旋转、翻转或旋转并翻转图像。

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | rotate flip 的类型。 |

## 示例

此示例演示了在图像上使用 Rotate 操作。示例从某个磁盘位置加载现有图像文件，并根据枚举 Aspose.PSD.RotateFlipType 的值对图像执行 Rotate 操作

```csharp
[C#]

//创建 image 类的实例，并通过文件路径使用现有图像文件进行初始化
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //将图像绕 X 轴旋转 180 度
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // 保存所有更改。
    image.Save();
}
```

### 另请参阅

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


