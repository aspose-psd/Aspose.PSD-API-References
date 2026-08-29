---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Eigenschaft. Ruft den globalen Winkel ab oder legt ihn fest"
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Liest oder setzt den globalen Winkel.

```csharp
public int GlobalAngle { get; set; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung der Eigenschaft PsdImage.GlobalAngle, um den globalen Winkelwert zu ändern.

```csharp
[C#]

// Wenn die Eigenschaft DropShadowEffect.UseGlobalLight den Wert 'true' hat, verwendet das DropShadowEffect-Objekt den Winkelwert aus der Eigenschaft PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Siehe auch

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


