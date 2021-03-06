---
title: Resize
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 190
url: /net/aspose.psd/image/resize/
---
## Image.Resize method (1 of 3)

Resizes the image. The default LeftTopToLeftTop is used.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |

### Examples

The following example demonstrates how to resize PSD image and result we get by Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(160, 120);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### See Also

* class [Image](../../image)
* namespace [Aspose.PSD](../../image)
* assembly [Aspose.PSD](../../../)

---

## Image.Resize method (2 of 3)

Resizes the image.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| resizeType | ResizeType | The resize type. |

### See Also

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* namespace [Aspose.PSD](../../image)
* assembly [Aspose.PSD](../../../)

---

## Image.Resize method (3 of 3)

Resizes the image.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | The new width. |
| newHeight | Int32 | The new height. |
| settings | ImageResizeSettings | The resize settings. |

### See Also

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* namespace [Aspose.PSD](../../image)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
