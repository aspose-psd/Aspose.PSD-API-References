---
title: "SmartObjectLayer.Contents"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "SmartObjectLayer प्रॉपर्टी। स्मार्ट ऑब्जेक्ट लेयर की सामग्री प्राप्त या सेट करता है। एम्बेडेड स्मार्ट ऑब्जेक्ट की सामग्री एम्बेडेड रॉ इमेज फ़ाइल Data और उसकी प्रॉपर्टीज़ है। लिंक्ड स्मार्ट ऑब्जेक्ट की सामग्री लिंक्ड इमेज फ़ाइल की रॉ सामग्री है यदि वह उपलब्ध है और उसकी प्रॉपर्टीज़ LiFeDataSource हैं। जब IsLibraryLink true हो तो हम Adobe Photoshop ग्राफ़िक्स लाइब्रेरी से लोडिंग का समर्थन नहीं करते। सामान्य लिंक फ़ाइलों के लिए पहले हम RelativePath का उपयोग करके फ़ाइल को स्रोत इमेज पाथ SourceImagePath के सापेक्ष खोजते हैं; यदि उपलब्ध नहीं है तो FullPath को देखते हैं; यदि फिर भी नहीं मिलता तो लिंक फ़ाइल को उसी डायरेक्टरी में खोजते हैं जहाँ हमारी इमेज SourceImagePath स्थित है।"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
{{< psd/tize >}}
## SmartObjectLayer.Contents property

स्मार्ट ऑब्जेक्ट लेयर की सामग्री प्राप्त या सेट करता है। एम्बेडेड स्मार्ट ऑब्जेक्ट की सामग्री एम्बेडेड रॉ इमेज फ़ाइल है: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) और उसकी प्रॉपर्टीज़। लिंक्ड स्मार्ट ऑब्जेक्ट की सामग्री लिंक्ड इमेज फ़ाइल की रॉ सामग्री है यदि वह उपलब्ध है और उसकी प्रॉपर्टीज़: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)। जब [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) true हो तो हम Adobe Photoshop ग्राफ़िक्स लाइब्रेरी से लोडिंग का समर्थन नहीं करते। सामान्य लिंक फ़ाइलों के लिए, पहले हम [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) का उपयोग करके फ़ाइल को स्रोत इमेज पाथ SourceImagePath के सापेक्ष खोजते हैं; यदि उपलब्ध नहीं है तो [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) को देखते हैं; यदि फिर भी नहीं मिलता तो लिंक फ़ाइल को उसी डायरेक्टरी में खोजते हैं जहाँ हमारी इमेज स्थित है: SourceImagePath।

```csharp
public byte[] Contents { get; set; }
```

### Property Value

बाइट[] स्मार्ट ऑब्जेक्ट लेयर की सामग्री।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| NotSupportedException | Adobe Photoshop लाइब्रेरी से सामग्री प्राप्त नहीं की जा सकती। |

## उदाहरण

निम्नलिखित कोड एम्बेडेड स्मार्ट ऑब्जेक्ट्स के समर्थन को दर्शाता है।

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// यह उदाहरण दिखाता है कि PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर को कैसे बदलें और स्मार्ट ऑब्जेक्ट की मूल एम्बेडेड सामग्री को निर्यात/अपडेट करें।
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

        // आइए PSD स्मार्ट ऑब्जेक्ट लेयर से एम्बेडेड स्मार्ट ऑब्जेक्ट इमेज को निर्यात करें
        smartObjectLayer.ExportContents(exportPath);

        // आइए जांचें कि मूल इमेज सही तरीके से सहेजी गई है या नहीं
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // आइए मूल स्मार्ट ऑब्जेक्ट इमेज को उलटें
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // आइए PSD लेयर में एम्बेडेड स्मार्ट ऑब्जेक्ट इमेज को बदलें
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // आइए जांचें कि अपडेटेड इमेज सही तरीके से सहेजी गई है या नहीं
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### देखें भी

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


