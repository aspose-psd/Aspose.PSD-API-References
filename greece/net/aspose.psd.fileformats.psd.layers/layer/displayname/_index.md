---
title: Layer.DisplayName
second_title: Aspose.PSD για Αναφορά API .NET
description: Layer ιδιοκτησία. Λαμβάνει ή ορίζει το εμφανιζόμενο όνομα του επιπέδου.
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Λαμβάνει ή ορίζει το εμφανιζόμενο όνομα του επιπέδου.

```csharp
public string DisplayName { get; set; }
```

### Αξία περιουσίας

Το εμφανιζόμενο όνομα του επιπέδου.

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει τη δυνατότητα να ορίσετε την τιμή DisplayName, σε αυτό που εμφανίζεται σωστά το όνομα του επιπέδου.

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* συνέλευση [Aspose.PSD](../../../)


