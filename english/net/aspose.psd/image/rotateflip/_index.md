---
title: Image.RotateFlip
second_title: Aspose.PSD for .NET API Reference
description: Image method. Rotates flips or rotates and flips the image
type: docs
weight: 220
url: /net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Rotates, flips, or rotates and flips the image.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Type of the rotate flip. |

## Examples

This example demonstrates the use of Rotate operation on an image. Example loads an existing image file from some disk location and performs the Rotate operation on the image according to the value of Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Create an instance of image class and initialize it with an existing image file through File path
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Rotate the image at 180 degree about X axis
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // save all changes.
    image.Save();
}
```

### See Also

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../image/)
* assembly [Aspose.PSD](../../../)


