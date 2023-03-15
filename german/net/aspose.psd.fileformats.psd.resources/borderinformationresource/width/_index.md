---
title: BorderInformationResource.Width
second_title: Aspose.PSD für .NET-API-Referenz
description: BorderInformationResource eigendom. Ruft die Rahmenbreite ab oder legt sie fest.
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
## BorderInformationResource.Width property

Ruft die Rahmenbreite ab oder legt sie fest.

```csharp
public double Width { get; set; }
```

### Beispiele

Das folgende Beispiel veranschaulicht die Unterstützung der BorderInformationResource-Ressource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource aktualisieren
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Siehe auch

* class [BorderInformationResource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* Montage [Aspose.PSD](../../../)


