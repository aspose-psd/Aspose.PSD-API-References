---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdLoadOptions 属性。获取或设置在渲染时如果图层未被修改是否保留原始图层像素"
type: docs
weight: 20
url: /zh/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

获取或设置在渲染期间是否在图层未被修改时保留原始图层像素。

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` 表示保留未更改图层的原始像素；否则为 `false`。

## 示例

以下代码演示了在更改之前防止图层自动重绘的新行为。

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### 另请参阅

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


