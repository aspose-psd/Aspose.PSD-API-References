---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 属性。获取或设置全局角度"
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

获取或设置全局角度。

```csharp
public int GlobalAngle { get; set; }
```

## 示例

以下代码演示了对 PsdImage.GlobalAngle 属性的支持，以更改全局角度值。

```csharp
[C#]

// 当 DropShadowEffect.UseGlobalLight 属性为 'true' 时，DropShadowEffect 对象将使用来自 PsdImage.GlobalAngle 属性的角度值。

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### 另请参阅

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


