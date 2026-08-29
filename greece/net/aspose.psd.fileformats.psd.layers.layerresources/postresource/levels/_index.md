---
title: "PostResource.Levels"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PostResource. Επίπεδα της στρώσης Posterize"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Επίπεδα του Posterize layer.

```csharp
public short Levels { get; set; }
```

### Τιμή Επιστροφής

Τιμή int Levels

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα χειρισμού του PostResource.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### Δείτε επίσης

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


