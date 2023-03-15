---
title: SmartObjectLayer.NewSmartObjectViaCopy
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: SmartObjectLayer तरक. इसे कप करके एक नय स्मर्ट ऑब्जेक्ट लेयर बनत है लेयर  स्मर्ट ऑब्जेक्ट्स  कप के मध्यम से नई स्मर्ट ऑब्जेक्ट क Adobe Photoshop क कर्यक्षमत क पुन उत्पन्न करत है ध्यन दें क यह केवल एम्बेडेड स्मर्ट ऑब्जेक्ट्स के लए सक्षम है क्यंक एम्बेडेड छव भ कप कय जत है यद आप एम्बेडेड छव उपयग क सझ करन चहते हैंDuplicateLayer वध.
type: docs
weight: 120
url: /hi/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
## SmartObjectLayer.NewSmartObjectViaCopy method

इसे कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है। 'लेयर -&gt; स्मार्ट ऑब्जेक्ट्स -&gt; कॉपी' के माध्यम से नई स्मार्ट ऑब्जेक्ट को Adobe� Photoshop की कार्यक्षमता को पुन: उत्पन्न करता है। ध्यान दें कि यह केवल एम्बेडेड स्मार्ट ऑब्जेक्ट्स के लिए सक्षम है क्योंकि एम्बेडेड छवि भी कॉपी किया जाता है। यदि आप एम्बेडेड छवि उपयोग को साझा करना चाहते हैं[`DuplicateLayer`](../duplicatelayer/) विधि.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### प्रतिलाभ की मात्रा

क्लोन[`SmartObjectLayer`](../) उदाहरण।

### उदाहरण

ये उदाहरण प्रदर्शित करते हैं कि PSD छवि में स्मार्ट ऑब्जेक्ट परतों की प्रतिलिपि कैसे बनाई जाए।

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// ये उदाहरण प्रदर्शित करते हैं कि PSD छवि में स्मार्ट ऑब्जेक्ट परतों की प्रतिलिपि कैसे बनाई जाए।
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // कॉपी करने के लिए परत संख्या
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // एम्बेडेड स्मार्ट ऑब्जेक्ट इमेज को उल्टा करते हैं (आंतरिक PSD छवि के लिए हम केवल इसकी पहली परत को उल्टा करते हैं)
            InvertImage(innerImage);

            // आइए एम्बेडेड स्मार्ट ऑब्जेक्ट छवि को PSD परत में बदलें
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // डुप्लीकेट लेयर अपनी एम्बेडेड छवि को मूल स्मार्ट ऑब्जेक्ट के साथ साझा करती है
        // और इसे स्पष्ट रूप से अपडेट किया जाना चाहिए अन्यथा इसका रेंडरिंग कैश अपरिवर्तित रहता है।
        // हम यह सुनिश्चित करने के लिए प्रत्येक स्मार्ट ऑब्जेक्ट को अपडेट करते हैं कि NewSmartObjectViaCopy द्वारा बनाई गई नई परत
        // एम्बेडेड छवि को दूसरों के साथ साझा नहीं करता है।
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// PSD छवि सहित रेखापुंज छवि को उलट देता है।
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// रेखापुंज छवि को उलट देता है।
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### यह सभी देखें

* class [SmartObjectLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* सभा [Aspose.PSD](../../../)


