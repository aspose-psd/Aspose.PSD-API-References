---
title: "BackgroundColorResource.Color"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BackgroundColorResource-Eigenschaft. Gibt die Hintergrundfarbe zurück oder legt sie fest"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
{{< psd/tize >}}
## BackgroundColorResource.Color property

Liest oder setzt die Hintergrundfarbe.

```csharp
public Color Color { get; set; }
```

## Beispiele

Das folgende Beispiel demonstriert die Unterstützung der BackgroundColorResource-Ressource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // BackgroundColorResource aktualisieren
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Siehe auch

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


