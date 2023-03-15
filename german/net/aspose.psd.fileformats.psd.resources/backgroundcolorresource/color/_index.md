---
title: BackgroundColorResource.Color
second_title: Aspose.PSD für .NET-API-Referenz
description: BackgroundColorResource eigendom. Ruft die Hintergrundfarbe ab oder legt sie fest.
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Ruft die Hintergrundfarbe ab oder legt sie fest.

```csharp
public Color Color { get; set; }
```

### Beispiele

Das folgende Beispiel veranschaulicht die Unterstützung der BackgroundColorResource-Ressource.

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
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* Montage [Aspose.PSD](../../../)


