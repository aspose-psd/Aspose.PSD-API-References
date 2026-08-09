---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD for .NET API 参考"
description: "Layer 方法。将图层遮罩应用到图层，然后删除遮罩"
type: docs
weight: 350
url: /zh/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

将图层遮罩应用到图层，然后删除遮罩。

```csharp
public void ApplyLayerMask()
```

## 示例

以下代码演示了将遮罩应用到图层的功能。

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


