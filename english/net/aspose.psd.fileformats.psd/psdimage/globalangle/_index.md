---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD for .NET API Reference
description: PsdImage property. Gets or sets the global angle
type: docs
weight: 100
url: /net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Gets or sets the global angle.

```csharp
public int GlobalAngle { get; set; }
```

## Examples

The following code demonstrates support for the PsdImage.GlobalAngle property to change the global angle value.

```csharp
[C#]

// When DropShadowEffect.UseGlobalLight property is 'true', then DropShadowEffect object use angle value from PsdImage.GlobalAngle property.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### See Also

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


