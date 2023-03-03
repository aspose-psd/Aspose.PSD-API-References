---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD for .NET API 参考
description: PsdImage 财产. 获取或设置全局角度
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

获取或设置全局角度。

```csharp
public int GlobalAngle { get; set; }
```

### 例子

以下代码演示了对 PsdImage.GlobalAngle 属性的支持以更改全局角度值。

```csharp
[C#]

// 当 DropShadowEffect.UseGlobalLight 属性为“true”时，DropShadowEffect 对象使用 PsdImage.GlobalAngle 属性中的角度值。

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### 也可以看看

* class [PsdImage](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 部件 [Aspose.PSD](../../../)


