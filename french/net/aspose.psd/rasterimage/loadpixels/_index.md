---
title: "RasterImage.LoadPixels"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode RasterImage. Charge les pixels."
type: docs
weight: 410
url: /fr/net/aspose.psd/rasterimage/loadpixels/
---
{{< psd/tize >}}
## RasterImage.LoadPixels method

Charge des pixels.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle à partir duquel charger les pixels. |

### Valeur de retour

Le tableau de pixels chargé.

## Exemples

Cet exemple montre comment charger les informations de pixels dans un tableau de type Color, manipuler le tableau et le réaffecter à l'image. Pour effectuer ces opérations, cet exemple crée un nouveau fichier Image (au format PSD) en utilisant l'objet MemoryStream.

```csharp
[C#]

//Créez une instance de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Créez une instance de PsdOptions et définissez ses différentes propriétés, y compris la propriété Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Créez une instance d'Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Obtenez les pixels de l'image en spécifiant la zone comme limite de l'image
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Parcourez le tableau et définissez la couleur du pixel indexé alternatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Définissez la couleur du pixel indexé sur jaune
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Définissez la couleur du pixel indexé sur bleu
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Appliquez les modifications de pixels à l'image
        image.SavePixels(image.Bounds, pixels);

        // Enregistrez toutes les modifications.
        image.Save();
    }

    //Écrivez le MemoryStream dans un fichier
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Voir aussi

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


