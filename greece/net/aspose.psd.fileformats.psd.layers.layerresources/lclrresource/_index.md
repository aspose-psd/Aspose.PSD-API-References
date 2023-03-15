---
title: Class LclrResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource τάξη. Κατηγορία LclrResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με το χρώμα του επιπέδου στη λίστα επιπέδων είναι PS. Είναι μόνο
type: docs
weight: 2620
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Κατηγορία LclrResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με το χρώμα του επιπέδου στη λίστα επιπέδων είναι PS. Είναι μόνο

```csharp
public class LclrResource : LayerResource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`LclrResource` τάξη. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Αρχικοποιεί μια νέα παρουσία του`LclrResource` τάξη. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Αρχικοποιεί μια νέα παρουσία του`LclrResource` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα του στρώματος. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | Λαμβάνει την έκδοση psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | Παίρνει την υπογραφή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Το κλειδί πληροφοριών εργαλείου τύπου. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


