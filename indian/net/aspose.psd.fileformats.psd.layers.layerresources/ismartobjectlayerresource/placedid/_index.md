---
title: ISmartObjectLayerResource.PlacedId
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ISmartObjectLayerResource संपत्त. PSD इमेज में इस स्मर्ट ऑब्जेक्ट लेयर डेट क वशष्ट पहचनकर्त प्रप्त य सेट करत है
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/
---
## ISmartObjectLayerResource.PlacedId property

PSD इमेज में इस स्मार्ट ऑब्जेक्ट लेयर डेटा का विशिष्ट पहचानकर्ता प्राप्त या सेट करता है।

```csharp
public Guid PlacedId { get; set; }
```

### संपत्ति मूल्य

इस स्मार्ट ऑब्जेक्ट लेयर रिसोर्स का विशिष्ट पहचानकर्ता।

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

* interface [ISmartObjectLayerResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ismartobjectlayerresource/)
* सभा [Aspose.PSD](../../../)

