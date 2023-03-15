---
title: Class SoCoResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource τάξη. Κατηγορία SoCoResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με το Color Fill Layers
type: docs
weight: 3010
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Κατηγορία SoCoResource. Αυτός ο πόρος περιέχει πληροφορίες σχετικά με το Color Fill Layers

```csharp
public class SoCoResource : FillLayerResource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [SoCoResource](socoresource/)() | Αρχικοποιεί μια νέα παρουσία του`SoCoResource` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | Παίρνει το χρώμα RGB . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 δεν υποδηλώνει περιορισμούς. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | Λαμβάνει την υπογραφή του πόρου του επιπέδου. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | Το κλειδί πληροφοριών εργαλείου τύπου. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς επεξεργάζεστε το SoCoResource (Layer Resource for Color Fill Layer)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Εύρεση FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Εύρεση SoCoResource στη λίστα πόρων επιπέδου
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Ρύθμιση της ιδιότητας SoCoResource Color
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Δείτε επίσης

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


