---
title: "BorderInformationResource.DataSize"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BorderInformationResource. Obtient la taille des données de la ressource en octets"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

Obtient la taille des données de la ressource en octets.

```csharp
public override int DataSize { get; }
```

### Property Value

La taille des données de la ressource.

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


