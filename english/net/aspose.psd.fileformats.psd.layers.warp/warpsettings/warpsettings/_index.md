---
title: WarpSettings.WarpSettings
second_title: Aspose.PSD for .NET API Reference
description: WarpSettings constructor. Initializes a new instance of the WarpSettings class
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Initializes a new instance of the [`WarpSettings`](../) class.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| meshPoints | PointF[] | The mesh points of warp |
| bounds | Rectangle | The bounds of warp image |

## Examples

The following code demonstrates support of WarpSettings.GridSize property.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Get warp settings
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Set new size
    // For the Photoshop value can be between 1 and 50 and you can not save PSD file correctly.
    warpSettings.GridSize = new Size(100, 100);

    // Set valid value
    warpSettings.GridSize = new Size(3, 3);

    // Render example file with x3 grid
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### See Also

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Initializes a new instance of the [`WarpSettings`](../) class.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parameter | Type | Description |
| --- | --- | --- |
| meshPoints | PointF[] | The mesh points of warp |
| bounds | Rectangle | The bounds of warp image |
| style | WarpStyles | The style of warp |

## Examples

The following code demonstrates support of WarpSettings.GridSize property.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Get warp settings
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Set new size
    // For the Photoshop value can be between 1 and 50 and you can not save PSD file correctly.
    warpSettings.GridSize = new Size(100, 100);

    // Set valid value
    warpSettings.GridSize = new Size(3, 3);

    // Render example file with x3 grid
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### See Also

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Initializes a new instance of the [`WarpSettings`](../) class.

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | PS items with warp settings |
| bounds | Rectangle | The bounds of warp image |

### See Also

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Initializes a new instance of the [`WarpSettings`](../) class.

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parameter | Type | Description |
| --- | --- | --- |
| placedResource | PlacedResource | The resource with warp settings |

### See Also

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


