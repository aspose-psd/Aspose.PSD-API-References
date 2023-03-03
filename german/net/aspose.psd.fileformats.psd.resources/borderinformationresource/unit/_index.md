---
title: BorderInformationResource.Unit
second_title: Aspose.PSD für .NET-API-Referenz
description: BorderInformationResource eigendom. Ruft die Grenzeinheiten ab oder legt sie fest.
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

Ruft die Grenzeinheiten ab oder legt sie fest.

```csharp
public PhysicalUnit Unit { get; set; }
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

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* Montage [Aspose.PSD](../../../)


