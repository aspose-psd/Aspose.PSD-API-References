---
title: "SoCoResource.Color"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "SoCoResource ιδιότητα. Ανακτά το χρώμα RGB"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

Λαμβάνει το χρώμα RGB.

```csharp
public Color Color { get; set; }
```

### Τιμή Επιστροφής

Το χρώμα RGB

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς επεξεργάζεστε το SoCoResource (Πόρος στρώματος για στρώμα γεμίσματος χρώματος)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Εύρεση του FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Εύρεση του SoCoResource στη λίστα πόρων στρώματος
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

                    // Ρύθμιση της ιδιότητας Color του SoCoResource
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


