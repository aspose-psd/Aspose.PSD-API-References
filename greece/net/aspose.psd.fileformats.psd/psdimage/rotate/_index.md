---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος PsdImage. Περιστρέφει την εικόνα γύρω από το κέντρο"
type: docs
weight: 670
url: /el/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Περιστρέφει την εικόνα γύρω από το κέντρο.

```csharp
public override void Rotate(float angle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | Single | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές θα περιστρέφουν δεξιόστροφα. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα περιστροφής της εικόνας κατά συγκεκριμένη τιμή γωνίας.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Περιστροφή ολόκληρης εικόνας
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Περιστροφή επιπέδου
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Δείτε επίσης

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Περιστρέφει την εικόνα γύρω από το κέντρο.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | Single | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές θα περιστρέφουν δεξιόστροφα. |
| resizeProportionally | Boolean | εάν οριστεί σε `true` το μέγεθος της εικόνας θα αλλάξει σύμφωνα με τις προβολές του περιστρεφόμενου ορθογωνίου (σημεία γωνιών), διαφορετικά οι διαστάσεις θα παραμείνουν αμετάβλητες και μόνο τα εσωτερικά περιεχόμενα της εικόνας θα περιστραφούν. |
| backgroundColor | Χρώμα | Χρώμα του φόντου. |

### Δείτε επίσης

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


