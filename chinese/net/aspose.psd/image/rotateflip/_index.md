---
title: Image.RotateFlip
second_title: Aspose.PSD for .NET API 参考
description: Image 方法. 旋转翻转或旋转并翻转图像
type: docs
weight: 220
url: /zh/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

旋转、翻转或旋转并翻转图像。

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转的类型。 |

### 例子

这个例子演示了在图像上使用旋转操作。示例从某个磁盘位置加载现有图像文件，并根据 Enum Aspose.PSD.RotateFlipType 的值对图像执行旋转操作

```csharp
[C#]

//创建一个image类的实例，通过File路径用一个已经存在的图片文件初始化
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //图像绕X轴旋转180度
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // 保存所有更改。
    image.Save();
}
```

### 也可以看看

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* 命名空间 [Aspose.PSD](../../image/)
* 部件 [Aspose.PSD](../../../)


