---
title: "Layer.DisplayName"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα Layer. Λαμβάνει ή ορίζει το εμφανιζόμενο όνομα του επιπέδου"
type: docs
weight: 110
url: /el/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Λαμβάνει ή ορίζει το εμφανιζόμενο όνομα του επιπέδου.

```csharp
public string DisplayName { get; set; }
```

### Property Value

Το εμφανιζόμενο όνομα του επιπέδου.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει τη δυνατότητα ορισμού της τιμής DisplayName, ώστε το όνομα του επιπέδου να εμφανίζεται σωστά.

```csharp
[C#]

// κάντε αλλαγές στα ονόματα των επιπέδων και αποθηκεύστε το
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // ορίστε νέα τιμή στην ιδιότητα DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Δείτε επίσης

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


