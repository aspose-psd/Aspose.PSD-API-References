---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PixelDataFormat. Λαμβάνει το PixelDataFormat που ορίζεται για 64 bit ανά pixel με 16 bit για καθένα από τα άλφα, κόκκινο, πράσινο και μπλε."
type: docs
weight: 110
url: /el/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

Λαμβάνει το [`PixelDataFormat`](../) που ορίζεται για 64 bit ανά pixel με 16 bit για καθένα από τα άλφα, κόκκινο, πράσινο και μπλε.

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

Το [`PixelDataFormat`](../) που ορίζεται για 64 bit ανά pixel με 16 bit για καθένα από τα άλφα, κόκκινο, πράσινο και μπλε.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της κλάσης RawColor αντί της παλαιάς δομής Color.

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

### Δείτε επίσης

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


