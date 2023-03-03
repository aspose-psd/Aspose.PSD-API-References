---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdImage eigendom. Ruft den globalen Winkel ab oder legt ihn fest.
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Ruft den globalen Winkel ab oder legt ihn fest.

```csharp
public int GlobalAngle { get; set; }
```

### Beispiele

Der folgende Code demonstriert die Unterstützung für die PsdImage.GlobalAngle-Eigenschaft zum Ändern des globalen Winkelwerts.

```csharp
[C#]

// Wenn die DropShadowEffect.UseGlobalLight-Eigenschaft 'true' ist, dann verwendet das DropShadowEffect-Objekt den Winkelwert aus der PsdImage.GlobalAngle-Eigenschaft.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Siehe auch

* class [PsdImage](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Montage [Aspose.PSD](../../../)


