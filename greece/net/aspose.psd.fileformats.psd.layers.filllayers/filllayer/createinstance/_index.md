---
title: FillLayer.CreateInstance
second_title: Aspose.PSD για Αναφορά API .NET
description: FillLayer μέθοδος. Δημιουργήστε μια νέα παρουσία τουFillLayer κατηγορία ανά τύπο γεμίσματος.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Δημιουργήστε μια νέα παρουσία του[`FillLayer`](../) κατηγορία ανά τύπο γεμίσματος.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillType | FillType | Ο τύπος του στρώματος πλήρωσης. |

### Επιστρεφόμενη Αξία

Επιστρέφει μια νέα παρουσία του[`FillLayer`](../) κατηγορία ανά τύπο γεμίσματος.

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να προσθέσετε το επίπεδο τύπου FillLayer κατά το χρόνο εκτέλεσης.

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* συνέλευση [Aspose.PSD](../../../)


