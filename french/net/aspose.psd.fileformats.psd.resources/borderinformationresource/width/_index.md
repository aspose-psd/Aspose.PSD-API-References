---
title: "BorderInformationResource.Width"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BorderInformationResource. Obtient ou définit la largeur de la bordure"
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
{{< psd/tize >}}
## BorderInformationResource.Width property

Obtient ou définit la largeur de la bordure.

```csharp
public double Width { get; set; }
```

## Exemples

L'exemple suivant montre la prise en charge de la ressource BorderInformationResource.

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

    // mettre à jour BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Voir aussi

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


