---
title: "AiImage.SetPalette"
second_title: "Aspose.PSD for .NET API 参考"
description: "AiImage 方法。设置图像调色板"
type: docs
weight: 200
url: /zh/net/aspose.psd.fileformats.ai/aiimage/setpalette/
---
{{< psd/tize >}}
## AiImage.SetPalette method

设置图像调色板。

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 调色板 | IColorPalette | 要设置的调色板。 |
| updateColors | 布尔 | 如果设置为 `true`，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能导致图像加载时崩溃。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| NotImplementedException | 未实现 |

### 另请参阅

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


