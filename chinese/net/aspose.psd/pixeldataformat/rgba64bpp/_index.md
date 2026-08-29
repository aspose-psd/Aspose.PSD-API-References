---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Aspose.PSD for .NET API 参考"
description: "PixelDataFormat 属性。获取为每像素 64 位、每个 alpha、红、绿、蓝各 16 位定义的 PixelDataFormat。"
type: docs
weight: 110
url: /zh/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

获取为每像素 64 位、每个 alpha、红、绿、蓝各 16 位定义的 [`PixelDataFormat`](../)。

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

为每像素 64 位、每个 alpha、红、绿、蓝各 16 位定义的 [`PixelDataFormat`](../)。

## 示例

以下代码演示了使用 RawColor 类而不是已废弃的 Color 结构的支持。

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### 另请参阅

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


