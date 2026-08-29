---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα GifOptions. Λαμβάνει ή ορίζει την αναλογία πλευρών pixel του GIF"
type: docs
weight: 90
url: /el/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel του GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

Η αναλογία πλευρών pixel του GIF.

## Σχόλια

Pixel Aspect Ratio - Παράγοντας που χρησιμοποιείται για τον υπολογισμό μιας προσέγγισης της αναλογίας πλευρών του pixel στην αρχική εικόνα. Εάν η τιμή του πεδίου δεν είναι 0, αυτή η προσέγγιση της αναλογίας πλευρών υπολογίζεται βάσει του τύπου: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Η Pixel Aspect Ratio ορίζεται ως το πηλίκο του πλάτους του pixel προς το ύψος του. Η εμβέλεια τιμών σε αυτό το πεδίο επιτρέπει τον ορισμό του πιο πλατιάς pixel 4:1 έως του πιο ψηλού pixel 1:4 με βήματα 1/64. Τιμές : 0 - Δεν παρέχονται πληροφορίες για την αναλογία πλευρών. 1..255 - Τιμή που χρησιμοποιείται στον υπολογισμό.

### Δείτε επίσης

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


