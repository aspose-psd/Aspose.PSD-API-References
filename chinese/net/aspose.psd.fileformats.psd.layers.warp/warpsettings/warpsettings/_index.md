---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD for .NET API 参考"
description: "WarpSettings 构造函数。初始化 WarpSettings 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

初始化 [`WarpSettings`](../) 类的新实例。

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| meshPoints | PointF[] | warp 的网格点 |
| bounds | Rectangle | warp 图像的边界 |

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

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

初始化 [`WarpSettings`](../) 类的新实例。

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| meshPoints | PointF[] | warp 的网格点 |
| bounds | Rectangle | warp 图像的边界 |
| style | WarpStyles | warp 的样式 |

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

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

初始化 [`WarpSettings`](../) 类的新实例。

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | 带有 warp 设置的 PS 项目 |
| bounds | Rectangle | warp 图像的边界 |

### 另请参阅

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

初始化 [`WarpSettings`](../) 类的新实例。

```csharp
public WarpSettings(PlacedResource placedResource)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| placedResource | PlacedResource | 带有扭曲设置的资源 |

### 另请参阅

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


