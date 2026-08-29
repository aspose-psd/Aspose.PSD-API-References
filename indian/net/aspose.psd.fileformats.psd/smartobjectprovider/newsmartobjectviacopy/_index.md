---
title: "SmartObjectProvider.NewSmartObjectViaCopy"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "SmartObjectProvider मेथड। स्रोत लेयर की कॉपी करके नया स्मार्ट ऑब्जेक्ट लेयर बनाता है"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectProvider.NewSmartObjectViaCopy method

स्रोत लेयर की कॉपी करके नया स्मार्ट ऑब्जेक्ट लेयर बनाता है।

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | स्रोत लेयर। |

### रिटर्न वैल्यू

क्लोन किया गया [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) इंस्टेंस।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | आप केवल एक एम्बेडेड स्मार्ट ऑब्जेक्ट को बदल सकते हैं। |

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

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


