---
title: LayerHashCalculator.GetBlendingHash
second_title: Aspose.PSD för .NET API-referens
description: LayerHashCalculator metod. Hämtar blandningshash.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers/layerhashcalculator/getblendinghash/
---
## LayerHashCalculator.GetBlendingHash method

Hämtar blandnings-hash.

```csharp
public int GetBlendingHash()
```

### Returvärde

Unik hash för lagerblandningsalternativ

### Exempel

Följande kod visar API:et för att få den unika hashen för liknande lager i olika filer.

```csharp
[C#]

/// <summary>
/// Får namnet på lagret av.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="image">Bilden.</param>
/// <param name="namn">Namnet.</param>
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
/// Är det inte lika.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="expected">Det förväntade.</param>
/// <param name="actual">Det faktiska.</param>
/// <exception cref="System.Exception">Argument får inte vara lika</exception>
public static void AreNotEqual<T>(T expected, T actual)
{
    if (expected != null && expected.Equals(actual))
    {
        throw new Exception("Arguments must not be equal");
    }
}

/// <summary>
/// Ares lika.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="expected">Det förväntade.</param>
/// <param name="actual">Det faktiska.</param>
/// <exception cref="System.Exception">Argument måste vara lika</exception>
public static void AreEqual<T>(T expected, T actual)
{
    if (expected != null && !expected.Equals(actual))
    {
        throw new Exception("Arguments must be equal");
    }
}

/// <summary>
/// Regelverkar hashtestet för lagerinnehåll.
/// </summary>
/// <param name="filnamn">Namn på filen.</param>
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

        // Dessa lagers hash är lika
        AreEqual(hashers[0].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[4].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[6].GetChannelsHash());

        // Kontrollera blandningslägets hash 
        AreEqual(hashers[0].GetBlendingHash(), hashers[3].GetBlendingHash());
        AreEqual(hashers[1].GetBlendingHash(), hashers[4].GetBlendingHash());
        AreNotEqual(hashers[0].GetBlendingHash(), hashers[6].GetBlendingHash());

        // Men pekarna är olika
        AreNotEqual(layers[0], layers[3]);
        AreNotEqual(layers[1], layers[4]);
        AreNotEqual(layers[0], layers[6]);
    }
}

/// <summary>
/// Fyller hashtestet för lagerinnehåll.
/// </summary>
/// <param name="filnamn">Namn på filen.</param>
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

            // Liknande lager finns alltid i ett index
            AreEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[2].GetContentHash());
            AreEqual(colorFillHashers[1].GetContentHash(), colorFillHashers[3].GetContentHash());
            AreNotEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[1].GetContentHash());
        }
    }
}

/// <summary>
/// Smartar objektskiktets innehålls-hashtest.
/// </summary>
/// <param name="filnamn">Namn på filen.</param>
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

        // Kanaldata är lika för Layer och Createad från dessa smarta objekt.
        AreEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[4].GetChannelsHash());

        // Content Hash är annorlunda, eftersom Smart Object använder annan data som innehåll
        AreNotEqual(hashers[0].GetContentHash(), hashers[4].GetContentHash());

        // Men att blanda hash är liknande. Båda lagren – smarta och vanliga har Normal Blend-läge och opacitet 255
        AreEqual(hashers[0].GetBlendingHash(), hashers[4].GetBlendingHash());

        // Kanaldata är lika för Layer och Createad från dessa smarta objekt.
        AreEqual(hashers[1].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[5].GetChannelsHash());

        // Content Hash är annorlunda, eftersom Smart Object använder annan data som innehåll
        AreNotEqual(hashers[1].GetContentHash(), hashers[5].GetContentHash());
        // Men att blanda hash är liknande. Båda lagren – smarta och vanliga har Normal Blend-läge och opacitet 255
        AreEqual(hashers[1].GetBlendingHash(), hashers[5].GetBlendingHash());

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[2].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreNotEqual(hashers[4].GetChannelsHash(), hashers[5].GetChannelsHash());
    }
}

/// <summary>
/// Justerar lagerinnehållshashtestet.
/// </summary>
/// <param name="filnamn">Namn på filen.</param>
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

        // Alla hash måste vara olika
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
/// Textar lagrets innehåll hashtest.
/// </summary>
/// <param name="filnamn">Namn på filen.</param>
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

        // Transformationsmatris används inte i hashberäkning. Du bör dessutom kontrollera det
        AreEqual(textHashers2[0].GetContentHash(), textHashers2[4].GetContentHash());

        // I det här fallet har vi en rotation i matris
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[4].TransformMatrix);
        // I det här fallet har vi bara översättning (Textlager skiftat nedan)
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[1].TransformMatrix);
    }
}

/// <summary>
/// Grupperar hashtestet för lagerinnehåll.
/// </summary>
/// <param name="filnamn">Namn på filen.</param>
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

        // Group Layer Hash beräknas från lager inuti den
        AreEqual(groupLayersHashers[0].GetContentHash(), groupLayersHashers[1].GetContentHash());
        AreNotEqual(groupLayers[0], groupLayers[1]);
    }
}

/// <summary>
/// Regelar lagerinnehållet från olika filers hashtest.
/// </summary>
/// <param name="filnamn">Namn på filen.</param>
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

                // Lager har olika pekare
                AreNotEqual(layer, layer_copied);

                // Men hash av lager är lika
                AreEqual(hashCalc.GetChannelsHash(), hashCalc_copied.GetChannelsHash());
                AreEqual(hashCalc.GetContentHash(), hashCalc_copied.GetContentHash());
            }
        }
    }
    
    File.Delete(outputFile);
}
```

### Se även

* class [LayerHashCalculator](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layerhashcalculator/)
* hopsättning [Aspose.PSD](../../../)


