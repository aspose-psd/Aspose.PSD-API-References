---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage ιδιοκτησία. Λαμβάνει ή ορίζει την καθολική γωνία.
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Λαμβάνει ή ορίζει την καθολική γωνία.

```csharp
public int GlobalAngle { get; set; }
```

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει υποστήριξη για την ιδιότητα PsdImage.GlobalAngle για την αλλαγή της τιμής καθολικής γωνίας.

```csharp
[C#]

// Όταν η ιδιότητα DropShadowEffect.UseGlobalLight είναι "true", τότε το αντικείμενο DropShadowEffect χρησιμοποιεί την τιμή γωνίας από την ιδιότητα PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Δείτε επίσης

* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


