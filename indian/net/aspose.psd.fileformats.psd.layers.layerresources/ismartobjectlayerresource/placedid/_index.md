---
title: "ISmartObjectLayerResource.PlacedId"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ISmartObjectLayerResource प्रॉपर्टी। इस स्मार्ट ऑब्जेक्ट लेयर डेटा का अद्वितीय पहचानकर्ता प्राप्त या सेट करता है PSD छवि में"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/
---
{{< psd/tize >}}
## ISmartObjectLayerResource.PlacedId property

PSD इमेज में इस स्मार्ट ऑब्जेक्ट लेयर डेटा की विशिष्ट पहचानकर्ता को प्राप्त करता है या सेट करता है।

```csharp
public Guid PlacedId { get; set; }
```

### Property Value

इस स्मार्ट ऑब्जेक्ट लेयर संसाधन का अद्वितीय पहचानकर्ता।

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

* interface [ISmartObjectLayerResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


