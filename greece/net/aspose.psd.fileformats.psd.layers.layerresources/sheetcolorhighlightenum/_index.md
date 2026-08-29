---
title: "Απαρίθμηση SheetColorHighlightEnum"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum απαρίθμηση. Πιθανά χρώματα της ρύθμισης χρώματος Sheet. Το διακοσμητικό χρώμα UI του στρώματος στη λίστα στρωμάτων στο PS."
type: docs
weight: 3320
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

Πιθανά χρώματα της ρύθμισης χρώματος Φύλλου. Είναι διακοσμητικό χρώμα UI του στρώματος στη λίστα στρωμάτων στο PS.

```csharp
public enum SheetColorHighlightEnum : short
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| NoColor | `0` | Το χρώμα δεν έχει καθοριστεί. |
| Red | `1` | Το κόκκινο χρώμα. |
| Orange | `2` | Το πορτοκαλί χρώμα. |
| Yellow | `3` | Το κίτρινο χρώμα. |
| Green | `4` | Το πράσινο χρώμα. |
| Blue | `5` | Το μπλε χρώμα. |
| Violet | `6` | Το βιολετί χρώμα. |
| Gray | `7` | Το γκρι χρώμα. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να αλλάξετε το Sheet Color Highlight στο Aspose.PSD (ρύθμιση χρώματος Sheet).

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Στο αρχείο, τα χρώματα επισήμανσης των στρωμάτων είναι με αυτή τη σειρά.
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// Το Layer Sheet Color χρησιμοποιείται για οπτική επισήμανση των στρωμάτων.
// Για παράδειγμα, μπορείτε να ενημερώσετε κάποια στρώματα σε PSD και στη συνέχεια να επισημάνετε με χρώμα το στρώμα που θέλετε να τραβήξει την προσοχή.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Τα χρώματα πρέπει να αντιστραφούν.
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // Ο πόρος lcrl εμφανίζεται πάντα στη λίστα πόρων του αρχείου PSD.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Αντιστροφή των χρωμάτων του style sheet. Ρύθμιση του Layer color highlight.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


