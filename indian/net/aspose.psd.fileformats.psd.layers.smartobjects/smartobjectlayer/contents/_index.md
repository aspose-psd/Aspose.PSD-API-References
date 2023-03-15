---
title: SmartObjectLayer.Contents
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: SmartObjectLayer संपत्त. स्मर्ट ऑब्जेक्ट परत समग्र प्रप्त य सेट करत है एम्बेडेड स्मर्ट ऑब्जेक्ट समग्र एम्बेडेड कच्च छव फ़इल हैData और इसके गुण लंक क गई स्मर्ट ऑब्जेक्ट समग्र लंक क गई छव फ़इल क कच्च समग्र है यद यह उपलब्ध है और इसके गुण हैंLiFeDataSource . जब हम Adobe Photoshop  ग्रफ़क्स लइब्रेर से लड करने क समर्थन नहं करते हैंIsLibraryLink सत्य है. नयमत लंक फ़इलं के लए सबसे पहले हम उपयग करते हैंRelativePath स्रत छव पथ के लए फ़इल क अपेक्षकृत देखने के लएSourceImagePath  अगर यह उपलब्ध नहं है त हम देखते हैंFullPath  यद नहं त हम उस नर्देशक में लंक फ़इल क तलश करते हैं जहँ हमर छव हैSourceImagePath .
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

स्मार्ट ऑब्जेक्ट परत सामग्री प्राप्त या सेट करता है। एम्बेडेड स्मार्ट ऑब्जेक्ट सामग्री एम्बेडेड कच्ची छवि फ़ाइल है:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) और इसके गुण। लिंक की गई स्मार्ट ऑब्जेक्ट सामग्री लिंक की गई छवि फ़ाइल की कच्ची सामग्री है यदि यह उपलब्ध है और इसके गुण हैं:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . जब हम Adobe�� Photoshop� �� ग्राफ़िक्स लाइब्रेरी से लोड करने का समर्थन नहीं करते हैं[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) सत्य है. नियमित लिंक फ़ाइलों के लिए, सबसे पहले, हम उपयोग करते हैं[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) स्रोत छवि पथ के लिए फ़ाइल को अपेक्षाकृत देखने के लिएSourceImagePath , अगर यह उपलब्ध नहीं है तो हम देखते हैं[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , यदि नहीं तो हम उसी निर्देशिका में लिंक फ़ाइल की तलाश करते हैं जहाँ हमारी छवि है:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### संपत्ति मूल्य

दbyte[] स्मार्ट वस्तु परत सामग्री.

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| NotSupportedException | Adobe�� Photoshop �� लाइब्रेरी से सामग्री प्राप्त नहीं कर सकता। |

### उदाहरण

निम्नलिखित कोड एंबेडेड स्मार्ट ऑब्जेक्ट्स के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// यह उदाहरण दर्शाता है कि PSD फ़ाइल में स्मार्ट ऑब्जेक्ट परत को कैसे बदलना है और स्मार्ट ऑब्जेक्ट मूल एम्बेडेड सामग्री को निर्यात / अपडेट करना है।
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // चलिए PSD स्मार्ट ऑब्जेक्ट लेयर से एम्बेडेड स्मार्ट ऑब्जेक्ट इमेज को एक्सपोर्ट करते हैं
        smartObjectLayer.ExportContents(exportPath);

        // आइए देखें कि मूल छवि सही ढंग से सहेजी गई है या नहीं
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // आइए मूल स्मार्ट ऑब्जेक्ट इमेज को उल्टा करें
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // आइए एम्बेडेड स्मार्ट ऑब्जेक्ट छवि को PSD परत में बदलें
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // देखते हैं कि अपडेट की गई छवि सही ढंग से सहेजी गई है या नहीं
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### यह सभी देखें

* class [SmartObjectLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* सभा [Aspose.PSD](../../../)


