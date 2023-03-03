---
title: SoCoResource.Color
second_title: Aspose.PSD για Αναφορά API .NET
description: SoCoResource ιδιοκτησία. Παίρνει το χρώμα RGB .
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

Παίρνει το χρώμα RGB .

```csharp
public Color Color { get; set; }
```

### Επιστρεφόμενη Αξία

Το χρώμα RGB

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

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* συνέλευση [Aspose.PSD](../../../)


