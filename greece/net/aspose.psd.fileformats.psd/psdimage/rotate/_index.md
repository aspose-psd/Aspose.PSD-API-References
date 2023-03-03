---
title: PsdImage.Rotate
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage μέθοδος. Περιστροφή εικόνας γύρω από το κέντρο.
type: docs
weight: 610
url: /el/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Περιστροφή εικόνας γύρω από το κέντρο.

```csharp
public override void Rotate(float angle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | Single | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές θα περιστρέφονται δεξιόστροφα. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την ικανότητα περιστροφής της εικόνας κατά συγκεκριμένη τιμή γωνίας.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Ολόκληρη η εικόνα περιστρέφεται
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

// Περιστροφή στρώματος
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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Περιστροφή εικόνας γύρω από το κέντρο.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | Single | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές θα περιστρέφονται δεξιόστροφα. |
| resizeProportionally | Boolean | εάν έχει οριστεί σε`αληθής` θα αλλάξετε το μέγεθος της εικόνας σας σύμφωνα με τις προβολές περιστρεφόμενου ορθογωνίου (γωνιακά σημεία) σε άλλη περίπτωση που αφήνει ανέγγιχτες τις διαστάσεις και περιστρέφονται μόνο τα εσωτερικά περιεχόμενα της εικόνας. |
| backgroundColor | Color | Χρώμα φόντου. |

### Δείτε επίσης

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


