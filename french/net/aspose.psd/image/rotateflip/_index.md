---
title: "Image.RotateFlip"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Image. Effectue des rotations, des retournements ou des rotations et retournements de l'image"
type: docs
weight: 230
url: /fr/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Fait pivoter, retourner ou pivoter et retourner l'image.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Type de la rotation inversée. |

## Exemples

Cet exemple montre l'utilisation de l'opération Rotate sur une image. L'exemple charge un fichier image existant depuis un emplacement disque et effectue l'opération Rotate sur l'image selon la valeur de l'énumération Aspose.PSD.RotateFlipType

```csharp
[C#]

//Créer une instance de la classe image et l'initialiser avec un fichier image existant via le chemin de fichier
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Faire pivoter l'image de 180 degrés autour de l'axe X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // Enregistrez toutes les modifications.
    image.Save();
}
```

### Voir aussi

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


