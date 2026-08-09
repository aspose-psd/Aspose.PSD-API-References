---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdLoadOptions 属性。获取或设置是否在保存时使用带或不带扭曲变换的渲染图像"
type: docs
weight: 30
url: /zh/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

获取或设置是否使用渲染图像保存，是否带有或不带有扭曲变换。

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` 渲染图像时使用扭曲变换，`false` 不使用。

## 示例

以下代码演示了 Warp 效果的渲染。

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### 另请参阅

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


