---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur StreamSource. Initialise une nouvelle instance de la classe StreamSource"
type: docs
weight: 10
url: /fr/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Initialise une nouvelle instance de la classe [`StreamSource`](../).

```csharp
public StreamSource(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux à ouvrir. |

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

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initialise une nouvelle instance de la classe [`StreamSource`](../).

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux à ouvrir. |
| disposeStream | Booléen | si défini sur `true`, le flux sera libéré. |

## Exemples

Cet exemple montre l'utilisation de System.IO.Stream pour créer un nouveau fichier Image.

```csharp
[C#]

//Crée une instance de PsdOptions et définit ses différentes propriétés.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créez une instance de System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Définissez la propriété source pour l'instance de PsdOptions.
//Le deuxième paramètre booléen détermine si le Stream est libéré une fois sorti de la portée.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crée une instance d'Image et appelle la méthode Create avec PsdOptions comme paramètre pour initialiser l'objet Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Effectuez un traitement d'image.
}
```

### Voir aussi

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


