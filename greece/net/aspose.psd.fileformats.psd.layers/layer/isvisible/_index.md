---
title: "Layer.IsVisible"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα Layer. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το στρώμα είναι ορατό"
type: docs
weight: 180
url: /el/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στρώμα είναι ορατό

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` εάν αυτή η περίπτωση είναι ορατή· διαφορετικά, `false`.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να αλλάξετε την ορατότητα του LayerGroup στο Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// κάντε αλλαγές στα ονόματα των επιπέδων και αποθηκεύστε το
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Απενεργοποιήστε όλα μέσα σε μια ομάδα
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


