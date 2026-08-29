---
title: "BackgroundColorResource.Color"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BackgroundColorResource. Obtient ou définit la couleur d'arrière-plan"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
{{< psd/tize >}}
## BackgroundColorResource.Color property

Obtient ou définit la couleur d'arrière-plan.

```csharp
public Color Color { get; set; }
```

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

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


