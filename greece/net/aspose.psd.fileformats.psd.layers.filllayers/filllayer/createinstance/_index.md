---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος FillLayer. Δημιουργήστε μια νέα παρουσία της κλάσης FillLayer με βάση τον τύπο γεμίσματος."
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Δημιουργήστε μια νέα παρουσία της κλάσης [`FillLayer`](../) με βάση τον τύπο γεμίσματος.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillType | FillType | Ο τύπος της στρώσης γεμίσματος. |

### Τιμή Επιστροφής

Επιστρέφει μια νέα παρουσία της κλάσης [`FillLayer`](../) με βάση τον τύπο γεμίσματος.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε τη στρώση τύπου FillLayer κατά την εκτέλεση.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


