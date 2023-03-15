---
title: SmartObjectProvider.NewSmartObjectViaCopy
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: SmartObjectProvider तरक. स्रत क कप करके एक नई स्मर्ट ऑब्जेक्ट परत बनत है
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
## SmartObjectProvider.NewSmartObjectViaCopy method

स्रोत को कॉपी करके एक नई स्मार्ट ऑब्जेक्ट परत बनाता है।

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | स्रोत परत। |

### प्रतिलाभ की मात्रा

क्लोन किया गया[`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) उदाहरण.

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | आप केवल एम्बेडेड स्मार्ट ऑब्जेक्ट को बदल सकते हैं। |

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

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../smartobjectprovider/)
* सभा [Aspose.PSD](../../../)


