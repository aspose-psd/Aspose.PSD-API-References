---
title: "BackgroundColorResource.DataSize"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BackgroundColorResource. Obtient la taille des données de la ressource en octets"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

Obtient la taille des données de la ressource en octets.

```csharp
public override int DataSize { get; }
```

### Property Value

La taille des données de la ressource.

## Exemples

L'exemple suivant montre la prise en charge de la ressource BackgroundColorResource.

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

    // mettre à jour BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Voir aussi

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


