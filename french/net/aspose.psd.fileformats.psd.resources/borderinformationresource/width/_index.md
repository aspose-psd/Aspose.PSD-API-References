---
title: BorderInformationResource.Width
second_title: Référence de l'API Aspose.PSD pour .NET
description: BorderInformationResource propriété. Obtient ou définit la largeur de la bordure.
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
## BorderInformationResource.Width property

Obtient ou définit la largeur de la bordure.

```csharp
public double Width { get; set; }
```

### Exemples

L'exemple suivant illustre la prise en charge de la ressource BorderInformationResource.

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

    // met à jour BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Voir également

* class [BorderInformationResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* Assemblée [Aspose.PSD](../../../)


