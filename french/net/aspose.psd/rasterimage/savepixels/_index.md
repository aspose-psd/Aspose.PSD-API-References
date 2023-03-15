---
title: RasterImage.SavePixels
second_title: Référence de l'API Aspose.PSD pour .NET
description: RasterImage méthode. Enregistre les pixels.
type: docs
weight: 520
url: /fr/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Enregistre les pixels.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle dans lequel enregistrer les pixels. |
| pixels | Color[] | Le tableau de pixels. |

### Exemples

Cet exemple montre comment charger les informations de pixel dans un tableau de type couleur, manipuler le tableau et le redéfinir sur l'image. Pour effectuer ces opérations, cet exemple crée un nouveau fichier image (au format PSD) à l'aide de l'objet MemoryStream.

```csharp
[C#]

//Créer une instance de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Créer une instance de PsdOptions et définir ses différentes propriétés, y compris la propriété Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Créer une instance de Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // Récupère les pixels de l'image en spécifiant la zone comme limite de l'image
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // Boucle sur le tableau et définit la couleur du pixel indexé alternatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // Définit la couleur du pixel indexé sur jaune
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                // Définit la couleur du pixel indexé sur bleu
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Appliquer les changements de pixel à l'image
        image.SavePixels(image.Bounds, pixels);

        // Enregistrer toutes les modifications.
        image.Save();
    }

    // Écrire le flux de mémoire dans le fichier
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Voir également

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* espace de noms [Aspose.PSD](../../rasterimage/)
* Assemblée [Aspose.PSD](../../../)


