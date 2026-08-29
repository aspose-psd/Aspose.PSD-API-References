---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BackgroundColorResource. Obtient la version minimale requise du PSD"
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Obtient la version PSD minimale requise.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

La version PSD minimale.

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


