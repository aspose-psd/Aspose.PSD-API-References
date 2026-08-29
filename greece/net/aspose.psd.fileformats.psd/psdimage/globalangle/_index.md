---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdImage. Λαμβάνει ή ορίζει τη γωνία."
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Λαμβάνει ή ορίζει τη παγκόσμια γωνία.

```csharp
public int GlobalAngle { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας PsdImage.GlobalAngle για την αλλαγή της τιμής της παγκόσμιας γωνίας.

```csharp
[C#]

// Όταν η ιδιότητα DropShadowEffect.UseGlobalLight είναι 'true', τότε το αντικείμενο DropShadowEffect χρησιμοποιεί την τιμή γωνίας από την ιδιότητα PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Δείτε επίσης

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


