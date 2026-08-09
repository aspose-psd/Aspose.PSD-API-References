---
title: "LmskResource.ColorComponent1"
second_title: "Aspose.PSD for .NET API 参考"
description: "LmskResource 属性。获取颜色分量 1"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/
---
{{< psd/tize >}}
## LmskResource.ColorComponent1 property

获取颜色分量 1。

```csharp
public ushort ColorComponent1 { get; set; }
```

### Property Value

颜色分量 1。

## 示例

以下代码演示了如何通过更改 LmskResource 属性来更改 16 位图像的图层蒙版显示选项。

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 加载 16 位图像。
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // 查找 LmskResource。
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // 检查 LmskResource 属性。
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // 更改 LmskResource 属性。
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // 保存图像。
    image.Save(outputPsd);
}
```

### 另请参阅

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


