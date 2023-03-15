---
title: StreamSource.StreamSource
second_title: Référence de l'API Aspose.PSD pour .NET
description: StreamSource constructeur. Initialise une nouvelle instance duStreamSource classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Initialise une nouvelle instance du[`StreamSource`](../) classe.

```csharp
public StreamSource(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à ouvrir. |

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

* class [StreamSource](../)
* espace de noms [Aspose.PSD.Sources](../../streamsource/)
* Assemblée [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initialise une nouvelle instance du[`StreamSource`](../) classe.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux à ouvrir. |
| disposeStream | Boolean | si réglé sur`vrai` le flux sera éliminé. |

### Exemples

Cet exemple montre l'utilisation de System.IO.Stream pour créer un nouveau fichier image

```csharp
[C#]

// Crée une instance de PsdOptions et définit ses différentes propriétés
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créer une instance de System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Définir la propriété source pour l'instance de PsdOptions
// Le deuxième paramètre booléen détermine si le flux est éliminé une fois sorti de la portée
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

// Crée une instance de Image et appelle la méthode Create avec PsdOptions comme paramètre pour initialiser l'objet Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // faire du traitement d'image
}
```

### Voir également

* class [StreamSource](../)
* espace de noms [Aspose.PSD.Sources](../../streamsource/)
* Assemblée [Aspose.PSD](../../../)


