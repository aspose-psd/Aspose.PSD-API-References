---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum αρίθμηση. Πιθανά χρώματα της ρύθμισης χρώματος φύλλου. Είναι διακοσμητικό χρώμα διεπαφής του στρώματος στη λίστα στρώσεων σε PS
type: docs
weight: 2970
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

Πιθανά χρώματα της ρύθμισης χρώματος φύλλου. Είναι διακοσμητικό χρώμα διεπαφής του στρώματος στη λίστα στρώσεων σε PS

```csharp
public enum SheetColorHighlightEnum : short
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| NoColor | `0` | Το χρώμα δεν έχει καθοριστεί. |
| Red | `1` | Το κόκκινο χρώμα. |
| Orange | `2` | Το πορτοκαλί χρώμα. |
| Yellow | `3` | Το κίτρινο χρώμα. |
| Green | `4` | Το πράσινο χρώμα. |
| Blue | `5` | Το μπλε χρώμα. |
| Violet | `6` | Το βιολετί χρώμα. |
| Gray | `7` | Το γκρι χρώμα. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να αλλάξετε την επισήμανση χρώματος φύλλου στο Aspose.PSD (Ρύθμιση χρώματος φύλλου)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Στο αρχείο τα χρώματα της επισήμανσης των επιπέδων είναι με αυτή τη σειρά
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

// Το χρώμα φύλλου επιπέδων χρησιμοποιείται για την οπτική επισήμανση των επιπέδων. 
// Για παράδειγμα, μπορείτε να ενημερώσετε ορισμένα επίπεδα σε PSD και στη συνέχεια να επισημάνετε με χρώμα το επίπεδο που θέλετε να τραβήξετε την προσοχή.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Τα χρώματα πρέπει να αντιστραφούν
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
            // Ο πόρος lcrl εμφανίζεται πάντα στη λίστα πόρων αρχείων psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Αντίστροφη χρωμάτων φύλλου στυλ. Ρύθμιση της επισήμανσης χρώματος επιπέδου.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


