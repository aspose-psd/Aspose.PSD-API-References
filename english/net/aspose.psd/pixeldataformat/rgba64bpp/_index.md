---
title: PixelDataFormat.Rgba64Bpp
second_title: Aspose.PSD for .NET API Reference
description: PixelDataFormat property. Gets the PixelDataFormat defined for 64 bits per pixel with 16 bits for each of the alpha red green and blue
type: docs
weight: 110
url: /net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

Gets the [`PixelDataFormat`](../) defined for 64 bits per pixel with 16 bits for each of the alpha, red, green and blue.

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

The [`PixelDataFormat`](../) defined for 64 bits per pixel with 16 bits for each of the alpha, red, green and blue.

## Examples

The following code demonstrates the support of RawColor class instead of obsolete Color struct.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### See Also

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../pixeldataformat/)
* assembly [Aspose.PSD](../../../)


