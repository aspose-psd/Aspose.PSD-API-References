---
title: "PtFlResource.AlignWithLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PtFlResource. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν ευθυγραμμίζεται με το στρώμα"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/
---
{{< psd/tize >}}
## PtFlResource.AlignWithLayer property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `BaseGradientFillSettings` είναι με θόρυβο.

```csharp
public bool AlignWithLayer { get; set; }
```

### Property Value

`true` αν [ευθυγραμμίζεται με το στρώμα]; διαφορετικά, `false`.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει την υποστήριξη της φόρτωσης και επεξεργασίας ενός πόρου PtFlResource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // Ανάγνωση
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // Επεξεργασία
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Δεν έχουμε δεδομένα μοτίβου στο PattResource, οπότε μπορούμε να τα προσθέσουμε.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### Δείτε επίσης

* class [PtFlResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


