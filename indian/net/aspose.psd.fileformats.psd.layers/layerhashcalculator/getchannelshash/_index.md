---
title: LayerHashCalculator.GetChannelsHash
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LayerHashCalculator तरक. चैनल हैश ह जत है
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers/layerhashcalculator/getchannelshash/
---
## LayerHashCalculator.GetChannelsHash method

चैनल हैश हो जाता है।

```csharp
public int GetChannelsHash()
```

### प्रतिलाभ की मात्रा

सभी परत चैनलों का हैश

### उदाहरण

निम्न कोड अलग-अलग फाइलों में समान परतों के लिए अद्वितीय हैश प्राप्त करने के लिए एपीआई प्रदर्शित करता है।

```csharp
[C#]

/// <summary>
/// द्वारा परत का नाम प्राप्त करता है।
/// </summary>
/// <typeparam name="T"></typeparam>
/// <परम नाम="छवि">छवि.</परम>
/// <परम नाम="नाम">नाम.</परम>
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
/// बराबर नहीं हैं।
/// </summary>
/// <typeparam name="T"></typeparam>
/// <परम नाम="अपेक्षित">अपेक्षित.</परम>
/// <परम नाम="वास्तविक">वास्तविक.</परम>
/// <अपवाद cref="System.Exception">तर्क समान नहीं होने चाहिए</अपवाद>
public static void AreNotEqual<T>(T expected, T actual)
{
    if (expected != null && expected.Equals(actual))
    {
        throw new Exception("Arguments must not be equal");
    }
}

/// <summary>
/// बराबर हैं।
/// </summary>
/// <typeparam name="T"></typeparam>
/// <परम नाम="अपेक्षित">अपेक्षित.</परम>
/// <परम नाम="वास्तविक">वास्तविक.</परम>
/// <अपवाद cref="System.Exception">तर्क समान होने चाहिए</अपवाद>
public static void AreEqual<T>(T expected, T actual)
{
    if (expected != null && !expected.Equals(actual))
    {
        throw new Exception("Arguments must be equal");
    }
}

/// <summary>
/// परत सामग्री हैश परीक्षण को नियमित करता है।
/// </summary>
/// <param name="fileName">फ़ाइल का नाम.</param>
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

        // इन परतों का हैश बराबर है
        AreEqual(hashers[0].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[4].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[6].GetChannelsHash());

        // सम्मिश्रण मोड हैश की जाँच करें 
        AreEqual(hashers[0].GetBlendingHash(), hashers[3].GetBlendingHash());
        AreEqual(hashers[1].GetBlendingHash(), hashers[4].GetBlendingHash());
        AreNotEqual(hashers[0].GetBlendingHash(), hashers[6].GetBlendingHash());

        // लेकिन संकेत अलग हैं
        AreNotEqual(layers[0], layers[3]);
        AreNotEqual(layers[1], layers[4]);
        AreNotEqual(layers[0], layers[6]);
    }
}

/// <summary>
/// परत सामग्री हैश परीक्षण भरता है।
/// </summary>
/// <param name="fileName">फ़ाइल का नाम.</param>
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

            // समान परतें हमेशा एक अनुक्रमणिका में होती हैं
            AreEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[2].GetContentHash());
            AreEqual(colorFillHashers[1].GetContentHash(), colorFillHashers[3].GetContentHash());
            AreNotEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[1].GetContentHash());
        }
    }
}

/// <summary>
/// ऑब्जेक्ट लेयर कंटेंट हैश टेस्ट को स्मार्ट करता है।
/// </summary>
/// <param name="fileName">फ़ाइल का नाम.</param>
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

        // चैनल डेटा परत के लिए बराबर है और उनसे स्मार्ट ऑब्जेक्ट बनाएं।
        AreEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[4].GetChannelsHash());

        // कंटेंट हैश अलग है, क्योंकि स्मार्ट ऑब्जेक्ट अन्य डेटा को कंटेंट के रूप में उपयोग करता है
        AreNotEqual(hashers[0].GetContentHash(), hashers[4].GetContentHash());

        // लेकिन हैश सम्मिश्रण समान है। दोनों परतों - स्मार्ट और रेगुलर में नॉर्मल ब्लेंड मोड और अपारदर्शिता 255 है
        AreEqual(hashers[0].GetBlendingHash(), hashers[4].GetBlendingHash());

        // चैनल डेटा परत के लिए बराबर है और उनसे स्मार्ट ऑब्जेक्ट बनाएं।
        AreEqual(hashers[1].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[5].GetChannelsHash());

        // कंटेंट हैश अलग है, क्योंकि स्मार्ट ऑब्जेक्ट अन्य डेटा को कंटेंट के रूप में उपयोग करता है
        AreNotEqual(hashers[1].GetContentHash(), hashers[5].GetContentHash());
        // लेकिन हैश सम्मिश्रण समान है। दोनों परतों - स्मार्ट और रेगुलर में नॉर्मल ब्लेंड मोड और अपारदर्शिता 255 है
        AreEqual(hashers[1].GetBlendingHash(), hashers[5].GetBlendingHash());

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[2].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreNotEqual(hashers[4].GetChannelsHash(), hashers[5].GetChannelsHash());
    }
}

/// <summary>
/// परतों की सामग्री हैश परीक्षण समायोजित करता है।
/// </summary>
/// <param name="fileName">फ़ाइल का नाम.</param>
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

        // सभी हैश अलग होने चाहिए
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
/// परतों की सामग्री हैश परीक्षण का पाठ करता है।
/// </summary>
/// <param name="fileName">फ़ाइल का नाम.</param>
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

        // हैश गणना में परिवर्तन मैट्रिक्स का उपयोग नहीं किया जाता है। आपको इसकी अतिरिक्त जांच करनी चाहिए
        AreEqual(textHashers2[0].GetContentHash(), textHashers2[4].GetContentHash());

        // इस मामले में हमारे पास मैट्रिक्स में रोटेशन है
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[4].TransformMatrix);
        // इस मामले में हमारे पास केवल अनुवाद है (टेक्स्ट लेयर नीचे शिफ्ट किया गया है)
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[1].TransformMatrix);
    }
}

/// <summary>
/// परत सामग्री हैश परीक्षण को समूहीकृत करता है।
/// </summary>
/// <param name="fileName">फ़ाइल का नाम.</param>
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

        // ग्रुप लेयर हैश की गणना इसके अंदर की परतों से की जाती है
        AreEqual(groupLayersHashers[0].GetContentHash(), groupLayersHashers[1].GetContentHash());
        AreNotEqual(groupLayers[0], groupLayers[1]);
    }
}

/// <summary>
/// विभिन्न फ़ाइलों के हैश परीक्षण से परत सामग्री को नियमित करता है।
/// </summary>
/// <param name="fileName">फ़ाइल का नाम.</param>
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

                // परतों के अलग-अलग संकेत हैं
                AreNotEqual(layer, layer_copied);

                // लेकिन परतों का हैश बराबर है
                AreEqual(hashCalc.GetChannelsHash(), hashCalc_copied.GetChannelsHash());
                AreEqual(hashCalc.GetContentHash(), hashCalc_copied.GetContentHash());
            }
        }
    }
    
    File.Delete(outputFile);
}
```

### यह सभी देखें

* class [LayerHashCalculator](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layerhashcalculator/)
* सभा [Aspose.PSD](../../../)


