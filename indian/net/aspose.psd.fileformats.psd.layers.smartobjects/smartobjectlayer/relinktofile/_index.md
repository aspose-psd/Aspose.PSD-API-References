---
title: SmartObjectLayer.RelinkToFile
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: SmartObjectLayer तरक. लंक कए गए स्मर्ट ऑब्जेक्ट क एक नई फ़इल से दबर लंक करत है बद में UpdateModifiedContent वध क कल करने क कई आवश्यकत नहं है
type: docs
weight: 130
url: /hi/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/
---
## SmartObjectLayer.RelinkToFile method

लिंक किए गए स्मार्ट ऑब्जेक्ट को एक नई फ़ाइल से दोबारा लिंक करता है। बाद में UpdateModifiedContent विधि को कॉल करने की कोई आवश्यकता नहीं है।

```csharp
public void RelinkToFile(string linkedPath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| linkedPath | String | जुड़ा हुआ मार्ग। |

### उदाहरण

निम्न कोड लिंक्ड स्मार्ट ऑब्जेक्ट्स को अपडेट करने के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// यह उदाहरण दर्शाता है कि इन विधियों का उपयोग करके बाहरी या एम्बेडेड स्मार्ट ऑब्जेक्ट परत को कैसे अपडेट किया जाए:
// RelinkToFile, UpdateModifiedContent, ExportContents
ExampleOfUpdatingSmartObjectLayer("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfUpdatingSmartObjectLayer("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfUpdatingSmartObjectLayer(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // यह उदाहरण दर्शाता है कि PSD फ़ाइल में स्मार्ट ऑब्जेक्ट परत को कैसे बदलना है और इसकी सामग्री को निर्यात / अपडेट करना है।
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "updating_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_modified.png";
    string png2OutputPath = dataDir + fileName + "_updated_modified.png";
    string psd2OutputPath = dataDir + fileName + "_updated_modified.psd";
    string exportPath = dataDir + fileName + "_exported." + GetFormatExt(format);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        var contentType = smartObjectLayer.ContentType;
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        if (contentType == SmartObjectType.AvailableLinked)
        {
            Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
            // आइए PSD स्मार्ट ऑब्जेक्ट लेयर से बाहरी स्मार्ट ऑब्जेक्ट इमेज को एक नए स्थान पर निर्यात करें
            // क्योंकि हम इसे संशोधित करने जा रहे हैं।
            smartObjectLayer.ExportContents(exportPath);
            smartObjectLayer.RelinkToFile(exportPath);
        }

        // आइए स्मार्ट ऑब्जेक्ट की सामग्री को उल्टा करें: आंतरिक (कैश नहीं) छवि
        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(new LoadOptions()))
        {
            InvertImage(innerImage);
            using (var stream = new MemoryStream())
            {
                innerImage.Save(stream);
                smartObjectLayer.Contents = stream.ToArray();
            }
        }

        // देखते हैं कि संशोधित सामग्री अभी तक रेंडरिंग को प्रभावित नहीं करती है या नहीं।
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        smartObjectLayer.UpdateModifiedContent();

        // आइए देखें कि क्या अपडेट की गई सामग्री रेंडरिंग को प्रभावित करती है और पीएसडी छवि सही ढंग से सहेजी गई है
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// यह उदाहरण दर्शाता है कि ConvertToLinked विधि का उपयोग करके एम्बेडेड स्मार्ट ऑब्जेक्ट को बाहरी लिंक की गई सामग्री में कैसे परिवर्तित किया जाए।
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("new_panama-papers-4.psd", 0x10caa, 0, 0, 0x280, 0x169, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r3-embedded.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-tiff.psd", 0xca94, 0, 0, 0xb, 0x10, FileFormat.Tiff);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-bmp.psd", 0x278, 0, 0, 0xb, 0x10, FileFormat.Bmp);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-gif.psd", 0x3ec, 0, 0, 0xb, 0x10, FileFormat.Gif);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg.psd", 0x327, 0, 0, 0xb, 0x10, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg2000.psd", 0x519f, 0, 0, 0xb, 0x10, FileFormat.Jpeg2000);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-psd.psd", 0xc074, 0, 0, 0xb, 0x10, FileFormat.Psd);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfEmbeddedSmartObjectLayerToLinkedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // यह दर्शाता है कि PSD फ़ाइल में एम्बेडेड स्मार्ट ऑब्जेक्ट परत को बाहरी परत में कैसे परिवर्तित किया जाए।
    var formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_linked_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_external.png";
    string psdOutputPath = dataDir + fileName + "_to_external.psd";
    string externalPath = dataDir + fileName + "_external." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        Directory.CreateDirectory(Path.GetDirectoryName(externalPath));
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer.ConvertToLinked(externalPath);

        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        // देखते हैं कि परिवर्तित छवि सही ढंग से सहेजी गई है या नहीं
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);
    }
}

// यह उदाहरण दर्शाता है कि एंबेडलिंक विधि का उपयोग करके PSD फ़ाइल में एक बाहरी स्मार्ट ऑब्जेक्ट परत या सभी लिंक की गई परतों को कैसे एम्बेड किया जाए।
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
void ExampleOfLinkedSmartObjectLayerToEmbeddedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_embedded_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_embedded.png";
    string psdOutputPath = dataDir + fileName + "_to_embedded.psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer0 = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer0.EmbedLinked();
        AssertAreEqual(contentsLength, smartObjectLayer0.Contents.Length);
        AssertAreEqual(left, smartObjectLayer0.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer0.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer0.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer0.ContentsBounds.Bottom);
        if (image.Layers.Length >= 2)
        {
            var smartObjectLayer1 = (SmartObjectLayer)image.Layers[1];
            AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer0.ContentType);
            AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer1.ContentType);

            image.SmartObjectProvider.EmbedAllLinked();
            foreach (Layer layer in image.Layers)
            {
                var smartLayer = layer as SmartObjectLayer;
                if (smartLayer != null)
                {
                    AssertAreEqual(SmartObjectType.Embedded, smartLayer.ContentType);
                }
            }
        }

        Directory.CreateDirectory(Path.GetDirectoryName(psdOutputPath));
        // देखते हैं कि परिवर्तित छवि सही ढंग से सहेजी गई है या नहीं
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer.ContentType);
    }
}

// यह उदाहरण दर्शाता है कि Adobe® Photoshop® बाहरी स्मार्ट ऑब्जेक्ट परत को कैसे बदलना है और इसकी सामग्री को निर्यात / अपडेट करना है
// ExportContents और ReplaceContents विधियों का उपयोग करना।
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked2.psd", 0x4aea, 0, 0, 10, 10, FileFormat.Psd);
void ExampleOfExternalSmartObjectLayerSupport(string filePath, int contentsLength, int left, int top, int right, int bottom, FileFormat format)
{
    string formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "external_support_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + ".png";
    string psdOutputPath = dataDir + fileName + ".psd";
    string linkOutputPath = dataDir + fileName + "_inverted." + formatExt;
    string png2OutputPath = dataDir + fileName + "_updated.png";
    string psd2OutputPath = dataDir + fileName + "_updated.psd";
    string exportPath = dataDir + fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[image.Layers.Length - 1];
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
        // चलिए PSD स्मार्ट ऑब्जेक्ट लेयर से लिंक्ड स्मार्ट ऑब्जेक्ट इमेज को एक्सपोर्ट करते हैं
        smartObjectLayer.ExportContents(exportPath);

        // आइए देखें कि मूल छवि सही ढंग से सहेजी गई है या नहीं
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // आइए लिंक्ड स्मार्ट ऑब्जेक्ट इमेज को उल्टा करें
            InvertImage(innerImage);
            innerImage.Save(linkOutputPath);

            // आइए लिंक्ड स्मार्ट ऑब्जेक्ट इमेज को PSD लेयर में बदलें
            smartObjectLayer.ReplaceContents(linkOutputPath);
        }

        // देखते हैं कि अपडेट की गई छवि सही ढंग से सहेजी गई है या नहीं
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// छवि को उल्टा करता है।
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

// प्रारूप विस्तार प्राप्त करता है।
string GetFormatExt(FileFormat format)
{
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : format.ToString().ToLowerInvariant();
    return formatExt;
}
```

### यह सभी देखें

* class [SmartObjectLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* सभा [Aspose.PSD](../../../)


