---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD for .NET API 参考"
description: "WarpSettings 属性。获取或设置 warp 网格的大小。默认值为 1"
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

获取或设置扭曲网格的大小。默认值为 1。

```csharp
public Size GridSize { get; set; }
```

## 示例

以下代码演示了对 WarpSettings.GridSize 属性的支持。

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // 获取 warp 设置
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // 设置新大小
    // 对于 Photoshop，值可以在 1 到 50 之间，且无法正确保存 PSD 文件。
    warpSettings.GridSize = new Size(100, 100);

    // 设置有效值
    warpSettings.GridSize = new Size(3, 3);

    // 使用 x3 网格渲染示例文件
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### 另请参阅

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


