---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété AiImage. Obtient ou définit l'index de la page active"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Obtient ou définit l'index de la page active.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Cette propriété n'est applicable qu'aux images AI au format PDF. Si l'image n'est pas au format PDF ou s'il n'y a aucune page, la propriété sera -1. Cette propriété indique quelle page de l'image AI servira de base pour le rendu.

## Exemples

Le code suivant montre la prise en charge de la possibilité de changer la page active dans les images Ai.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Chargez l'image AI.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Par défaut, l'ActivePageIndex est 0.
    // Ainsi, si vous enregistrez l'image AI sans modifier cette propriété, la première page sera rendue et enregistrée.
    image.Save(firstPageOutputPng, new PngOptions());

    // Modifiez l'index de la page active à la deuxième page.
    image.ActivePageIndex = 1;

    // Enregistrez la deuxième page de l'image AI au format PNG.
    image.Save(secondPageOutputPng, new PngOptions());

    // Modifiez l'index de la page active à la troisième page.
    image.ActivePageIndex = 2;

    // Enregistrez la troisième page de l'image AI au format PNG.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Voir aussi

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


