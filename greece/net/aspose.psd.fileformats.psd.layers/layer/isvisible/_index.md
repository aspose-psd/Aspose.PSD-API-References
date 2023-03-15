---
title: Layer.IsVisible
second_title: Aspose.PSD για Αναφορά API .NET
description: Layer ιδιοκτησία. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το επίπεδο είναι ορατό
type: docs
weight: 170
url: /el/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το επίπεδο είναι ορατό

```csharp
public bool IsVisible { get; set; }
```

### Αξία περιουσίας

`αληθής` εάν αυτή η περίπτωση είναι ορατή. σε διαφορετική περίπτωση,`ψευδής` .

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να αλλάξετε την ορατότητα LayerGroup στο Aspose.PSD

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

        // Απενεργοποιήστε τα πάντα μέσα σε μια ομάδα
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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* συνέλευση [Aspose.PSD](../../../)


