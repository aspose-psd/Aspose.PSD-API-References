---
title: "SmartObjectLayer.NewSmartObjectViaCopy"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "SmartObjectLayer मेथड। इस लेयर को कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है। Adobe Photoshop की 'Layer → Smart Objects → New Smart Object via Copy' कार्यक्षमता को पुनः उत्पन्न करता है। ध्यान दें कि यह केवल एम्बेडेड स्मार्ट ऑब्जेक्ट्स के लिए सक्षम है क्योंकि एम्बेडेड इमेज भी कॉपी हो जाती है। यदि आप एम्बेडेड इमेज को साझा करना चाहते हैं तो DuplicateLayer मेथड का उपयोग करें"
type: docs
weight: 140
url: /hi/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectLayer.NewSmartObjectViaCopy method

इस लेयर को कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है। Adobe Photoshop की `Layer -> Smart Objects -> New Smart Object via Copy` कार्यक्षमता को पुनः उत्पन्न करता है। ध्यान दें कि यह केवल एम्बेडेड स्मार्ट ऑब्जेक्ट्स के लिए सक्षम है क्योंकि एम्बेडेड इमेज भी कॉपी हो जाती है। यदि आप एम्बेडेड इमेज को साझा करना चाहते हैं तो [`DuplicateLayer`](../duplicatelayer/) मेथड का उपयोग करें।

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### रिटर्न वैल्यू

क्लोन किया गया [`SmartObjectLayer`](../) इंस्टेंस।

## उदाहरण

ये उदाहरण दर्शाते हैं कि PSD इमेज में स्मार्ट ऑब्जेक्ट लेयर्स को कैसे कॉपी किया जाता है।

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// ये उदाहरण दर्शाते हैं कि PSD इमेज में स्मार्ट ऑब्जेक्ट लेयर्स को कैसे कॉपी किया जाता है।
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
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
            // चलिए एम्बेडेड स्मार्ट ऑब्जेक्ट इमेज को उलटते हैं (एक आंतरिक PSD इमेज के लिए हम केवल उसकी पहली लेयर को उलटते हैं)।
            InvertImage(innerImage);

            // आइए PSD लेयर में एम्बेडेड स्मार्ट ऑब्जेक्ट इमेज को बदलें
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // डुप्लिकेट की गई लेयर अपनी एम्बेडेड इमेज को मूल स्मार्ट ऑब्जेक्ट के साथ साझा करती है
        // और इसे स्पष्ट रूप से अपडेट किया जाना चाहिए, अन्यथा इसका रेंडरिंग कैश अपरिवर्तित रहेगा।
        // हम हर स्मार्ट ऑब्जेक्ट को अपडेट करते हैं ताकि यह सुनिश्चित हो सके कि NewSmartObjectViaCopy द्वारा बनाई गई नई लेयर
        // दूसरों के साथ एम्बेडेड इमेज साझा न करे।
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// रास्टर इमेज को उलटता है, जिसमें PSD इमेज भी शामिल है।
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

// रास्टर छवि को उलटता है।
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

### देखें भी

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


