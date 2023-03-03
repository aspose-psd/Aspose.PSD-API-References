---
title: LayerHashCalculator.GetContentHash
second_title: Référence de l'API Aspose.PSD pour .NET
description: LayerHashCalculator méthode. Obtient le hachage du contenu.
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers/layerhashcalculator/getcontenthash/
---
## LayerHashCalculator.GetContentHash method

Obtient le hachage du contenu.

```csharp
public int GetContentHash()
```

### Return_Value

Le hachage des paramètres significatifs des calques. Ce hachage est différent pour tous les types de couches

### Exemples

Le code suivant illustre l'API permettant d'obtenir le hachage unique pour des couches similaires dans différents fichiers.

```csharp
[C#]

/// <summary>
/// Obtient le nom de la couche par.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="image">L'image.</param>
/// <param name="name">Le nom.</param>
/// <returns></returns>
private static T GetLayerByName<T>(PsdImage image, string name) where T : Layer
{
    var layers = image.Layers;
    foreach (var layer in layers)
    {
        if (layer.Name == name)
        {
            return (T) layer;
        }
    }

    return null;
}

/// <summary>
/// Ares le pas égal.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="expected">L'attendu.</param>
/// <param name="réel">Le réel.</param>
/// <exception cref="System.Exception">Les arguments ne doivent pas être égaux</exception>
public static void AreNotEqual<T>(T expected, T actual)
{
    if (expected != null && expected.Equals(actual))
    {
        throw new Exception("Arguments must not be equal");
    }
}

/// <summary>
/// Ares l'égal.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="expected">L'attendu.</param>
/// <param name="réel">Le réel.</param>
/// <exception cref="System.Exception">Les arguments doivent être égaux</exception>
public static void AreEqual<T>(T expected, T actual)
{
    if (expected != null && !expected.Equals(actual))
    {
        throw new Exception("Arguments must be equal");
    }
}

/// <summary>
/// Régulier le test de hachage du contenu de la couche.
/// </summary>
/// <param name="fileName">Nom du fichier.</param>
public static void RegularLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var layers = new Layer[9];
        var hashers = new LayerHashCalculator[9];

        for (int i = 0; i < layers.Length; i++)
        {
            layers[i] = GetLayerByName<Layer>(im, string.Format("Layer {0}", i + 1));
            hashers[i] = new LayerHashCalculator(layers[i]);
        }

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[1].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreNotEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreNotEqual(hashers[5].GetChannelsHash(), hashers[7].GetChannelsHash());
        AreNotEqual(hashers[0].GetChannelsHash(), hashers[8].GetChannelsHash());

        // Les hachages de ces couches sont égaux
        AreEqual(hashers[0].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[4].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[6].GetChannelsHash());

        // Vérifier le hachage du mode de fusion 
        AreEqual(hashers[0].GetBlendingHash(), hashers[3].GetBlendingHash());
        AreEqual(hashers[1].GetBlendingHash(), hashers[4].GetBlendingHash());
        AreNotEqual(hashers[0].GetBlendingHash(), hashers[6].GetBlendingHash());

        // Mais les pointeurs sont différents
        AreNotEqual(layers[0], layers[3]);
        AreNotEqual(layers[1], layers[4]);
        AreNotEqual(layers[0], layers[6]);
    }
}

/// <summary>
/// Remplit le test de hachage du contenu du calque.
/// </summary>
/// <param name="fileName">Nom du fichier.</param>
public static void FillLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var fillLayersNames = new string[] { "Color Fill", "Gradient Fill", "Pattern Fill" };

        var colorFillLayers = new Layer[4];
        var colorFillHashers = new LayerHashCalculator[4];

        for (int fillLayerIndex = 0; fillLayerIndex < fillLayersNames.Length; fillLayerIndex++)
        {
            for (int i = 0; i < 2; i++)
            {
                var index = 0 + i * 2;
                colorFillLayers[index] = GetLayerByName<Layer>(im,
                    string.Format("{0} 1_{1}", fillLayersNames[fillLayerIndex], i + 1));
                colorFillHashers[index] = new LayerHashCalculator(colorFillLayers[index]);
                index = 1 + i * 2;
                colorFillLayers[index] = GetLayerByName<Layer>(im,
                    string.Format("{0} 2_{1}", fillLayersNames[fillLayerIndex], i + 1));
                colorFillHashers[index] = new LayerHashCalculator(colorFillLayers[index]);
            }

            // Les calques similaires sont toujours dans le même index
            AreEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[2].GetContentHash());
            AreEqual(colorFillHashers[1].GetContentHash(), colorFillHashers[3].GetContentHash());
            AreNotEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[1].GetContentHash());
        }
    }
}

/// <summary>
/// Smarts le test de hachage du contenu de la couche objet.
/// </summary>
/// <param name="fileName">Nom du fichier.</param>
public static void SmartObjectLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var smartObjects = new Layer[]
        {
            GetLayerByName<Layer>(im, "Regular1_1"),
            GetLayerByName<Layer>(im, "Regular1_2"),
            GetLayerByName<Layer>(im, "Regular2_1"),
            GetLayerByName<Layer>(im, "Regular2_2"),
            GetLayerByName<Layer>(im, "Smart1_1"),
            GetLayerByName<Layer>(im, "Smart1_2"),
            GetLayerByName<Layer>(im, "Smart2_1"),
            GetLayerByName<Layer>(im, "Smart2_2"),
        };

        var hashers = new LayerHashCalculator[smartObjects.Length];

        for (int i = 0; i < smartObjects.Length; i++)
        {
            hashers[i] = new LayerHashCalculator(smartObjects[i]);
        }

        // Les données de canal sont égales pour Layer et Createad à partir d'eux Smart Objects.
        AreEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[4].GetChannelsHash());

        // Content Hash est différent, car Smart Object utilise d'autres données comme contenu
        AreNotEqual(hashers[0].GetContentHash(), hashers[4].GetContentHash());

        // Mais mélanger le hachage est similaire. Les deux calques - intelligent et régulier ont le mode de fusion normale et une opacité de 255
        AreEqual(hashers[0].GetBlendingHash(), hashers[4].GetBlendingHash());

        // Les données de canal sont égales pour Layer et Createad à partir d'eux Smart Objects.
        AreEqual(hashers[1].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[5].GetChannelsHash());

        // Content Hash est différent, car Smart Object utilise d'autres données comme contenu
        AreNotEqual(hashers[1].GetContentHash(), hashers[5].GetContentHash());
        // Mais mélanger le hachage est similaire. Les deux calques - intelligent et régulier ont le mode de fusion normale et une opacité de 255
        AreEqual(hashers[1].GetBlendingHash(), hashers[5].GetBlendingHash());

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[2].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreNotEqual(hashers[4].GetChannelsHash(), hashers[5].GetChannelsHash());
    }
}

/// <summary>
/// Ajuste le test de hachage du contenu des calques.
/// </summary>
/// <param name="fileName">Nom du fichier.</param>
public static void AdjustmentLayersContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var adjustments = new Layer[]
        {
            GetLayerByName<Layer>(im, "Brightness/Contrast 1"),
            GetLayerByName<Layer>(im, "Levels 1"),
            GetLayerByName<Layer>(im, "Curves 1"),
            GetLayerByName<Layer>(im, "Exposure 1"),
            GetLayerByName<Layer>(im, "Vibrance 1"),
            GetLayerByName<Layer>(im, "Hue/Saturation 1"),
            GetLayerByName<Layer>(im, "Color Balance 1"),
            GetLayerByName<Layer>(im, "Black & White 1"),
            GetLayerByName<Layer>(im, "Photo Filter 1"),
            GetLayerByName<Layer>(im, "Channel Mixer 1"),
            GetLayerByName<Layer>(im, "Invert 1"),
            GetLayerByName<Layer>(im, "Posterize 1"),
        };

        var length = adjustments.Length;
        var hashers = new LayerHashCalculator[length];

        for (int i = 0; i < length; i++)
        {
            hashers[i] = new LayerHashCalculator(adjustments[i]);
        }

        // Tous les hachages doivent être différents
        for (int i = 0; i < length; i++)
        {
            for (int j = i + 1; j < length; j++)
            {
                AreNotEqual(hashers[i].GetContentHash(), hashers[j].GetContentHash());
                AreEqual(hashers[i].GetBlendingHash(), hashers[j].GetBlendingHash());
            }
        }
    }
}

/// <summary>
/// Texte le test de hachage du contenu des calques.
/// </summary>
/// <param name="fileName">Nom du fichier.</param>
public static void TextLayersContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var textLayers1 = new TextLayer[]
        {
            GetLayerByName<TextLayer>(im, "Text 1"),
            GetLayerByName<TextLayer>(im, "Text 1 Similar"),
            GetLayerByName<TextLayer>(im, "Text 1 Changed"),
        };

        var textLayers2 = new TextLayer[]
        {
            GetLayerByName<TextLayer>(im, "Text 2"),
            GetLayerByName<TextLayer>(im, "Text 2 Similar"),
            GetLayerByName<TextLayer>(im, "Text 2 Changed 1"),
            GetLayerByName<TextLayer>(im, "Text 2 Changed 2"),
            GetLayerByName<TextLayer>(im, "Text 2 Rotated"),
        };

        var textHashers1 = new LayerHashCalculator[textLayers1.Length];
        var textHashers2 = new LayerHashCalculator[textLayers2.Length];

        for (int i = 0; i < textLayers1.Length; i++)
        {
            textHashers1[i] = new LayerHashCalculator(textLayers1[i]);
        }

        for (int i = 0; i < textLayers2.Length; i++)
        {
            textHashers2[i] = new LayerHashCalculator(textLayers2[i]);
        }

        AreEqual(textHashers1[0].GetContentHash(), textHashers1[1].GetContentHash());
        AreNotEqual(textHashers1[0].GetContentHash(), textHashers1[2].GetContentHash());

        AreEqual(textHashers2[0].GetContentHash(), textHashers2[1].GetContentHash());

        AreNotEqual(textHashers2[0].GetContentHash(), textHashers2[2].GetContentHash());
        AreNotEqual(textHashers2[0].GetContentHash(), textHashers2[3].GetContentHash());

        // La matrice de transformation n'est pas utilisée dans le calcul de hachage. Vous devriez en plus le vérifier
        AreEqual(textHashers2[0].GetContentHash(), textHashers2[4].GetContentHash());

        // Dans ce cas, nous avons une rotation dans la matrice
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[4].TransformMatrix);
        // Dans ce cas, nous n'avons que la traduction (Couche de texte décalée ci-dessous)
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[1].TransformMatrix);
    }
}

/// <summary>
/// Regroupe le test de hachage du contenu de la couche.
/// </summary>
/// <param name="fileName">Nom du fichier.</param>
public static void GroupLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var fillLayersNames = new string[] { "Color Fill", "Gradient Fill", "Pattern Fill" };

        var groupLayers = new Layer[2];
        var groupLayersHashers = new LayerHashCalculator[2];

        groupLayers[0] = GetLayerByName<Layer>(im, "Fill");
        groupLayers[1] = GetLayerByName<Layer>(im, "Fill copy");

        for (int i = 0; i < groupLayers.Length; i++)
        {
            groupLayersHashers[i] = new LayerHashCalculator(groupLayers[i]);
        }

        // Group Layer Hash est calculé à partir des couches à l'intérieur
        AreEqual(groupLayersHashers[0].GetContentHash(), groupLayersHashers[1].GetContentHash());
        AreNotEqual(groupLayers[0], groupLayers[1]);
    }
}

/// <summary>
/// Régulier le contenu de la couche à partir de différents fichiers de test de hachage.
/// </summary>
/// <param name="fileName">Nom du fichier.</param>
public static void RegularLayerContentFromDifferentFilesHashTest(string fileName, string outputFile)
{
    using (var im = (PsdImage) Image.Load(fileName, new PsdLoadOptions() { ReadOnlyMode = true }))
    {
        im.Save(outputFile);
    }

    using (var im = (PsdImage) Image.Load(fileName))
    {
        using (var imCopied = (PsdImage) Image.Load(outputFile))
        {
            for (int i = 0; i < im.Layers.Length; i++)
            {
                var layer = im.Layers[i];
                var layer_copied = imCopied.Layers[i];
                var hashCalc = new LayerHashCalculator(layer);
                var hashCalc_copied = new LayerHashCalculator(layer_copied);

                // Les calques ont des pointeurs différents
                AreNotEqual(layer, layer_copied);

                // Mais le hachage des calques est égal
                AreEqual(hashCalc.GetChannelsHash(), hashCalc_copied.GetChannelsHash());
                AreEqual(hashCalc.GetContentHash(), hashCalc_copied.GetContentHash());
            }
        }
    }
    
    File.Delete(outputFile);
}
```

### Voir également

* class [LayerHashCalculator](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layerhashcalculator/)
* Assemblée [Aspose.PSD](../../../)


