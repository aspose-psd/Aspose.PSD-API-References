---
title: "Απαρίθμηση RenderQuality"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Περιγράφει την ποιότητα απόδοσης της παραμόρφωσης"
type: docs
weight: 3990
url: /el/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Περιγράφει την ποιότητα απόδοσης του Warp.

```csharp
public enum RenderQuality
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Turbo | `4` | Η πιο γρήγορη επιλογή, αλλά η ποιότητα υποφέρει. |
| VeryFast | `18` | Αν το χρειάζεστε γρήγορα, μπορεί να είναι κατάλληλο για μικρές καμπυλότητες. |
| Fast | `35` | Σας επιτρέπει να κάνετε την απόδοση πιο γρήγορη με μια μικρή μείωση στην ποιότητα. |
| Normal | `60` | Συνιστώμενη τιμή για τις περισσότερες καμπυλότητες |
| Good | `130` | Πιο υψηλή από την τυπική ποιότητα, πιο αργή ταχύτητα. Συνιστάται για ισχυρές παραμορφώσεις. |
| Excellent | `260` | Η πιο αργή επιλογή. Συνιστάται για ισχυρές παραμορφώσεις και υψηλές αναλύσεις. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την ιδιότητα WarpSettings.RenderQuality για τη διαμόρφωση της παραμόρφωσης του warp.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Λαμβάνει το WarpSettings από το Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Ορίζει το μέγεθος της περιοχής επεξεργασίας του warp
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Δεν θα πρέπει να υπάρχει σφάλμα εδώ
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


