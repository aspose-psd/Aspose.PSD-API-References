---
title: "Image.Create"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Image. Crée une nouvelle image en utilisant les options de création spécifiées"
type: docs
weight: 10
url: /fr/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Crée une nouvelle image en utilisant les options de création spécifiées.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Les options d'image. |
| largeur | Int32 | La largeur. |
| hauteur | Int32 | La hauteur. |

### Valeur de retour

L'image nouvellement créée.

## Exemples

Cet exemple crée un nouveau fichier Image à un emplacement disque spécifié par la propriété Source de l'instance PsdOptions. Plusieurs propriétés de l'instance PsdOptions sont définies avant la création de l'image réelle. En particulier la propriété Source, qui fait référence à l'emplacement disque réel dans ce cas.

```csharp
[C#]

//Créez une instance de PsdOptions et définissez ses différentes propriétés
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créez une instance de FileCreateSource et assignez‑la comme Source pour l'instance de PsdOptions
//Le deuxième paramètre booléen détermine si le fichier à créer est temporaire (IsTemporal) ou non
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Créez une instance d'Image et initialisez‑la avec une instance de PsdOptions en appelant la méthode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Effectuez un traitement d'image.

    // enregistrez toutes les modifications
    image.Save();
}
```

### Voir aussi

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


