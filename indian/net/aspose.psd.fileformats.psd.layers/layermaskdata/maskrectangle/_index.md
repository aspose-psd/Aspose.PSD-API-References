---
title: LayerMaskData.MaskRectangle
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LayerMaskData संपत्त. मस्क प्रप्त करत है य सेट करत हैRectanglePSD फ़इल में लेयर मस्क क यह बएँ दएँ ऊपर और नचे के गुणं क लेत है और बनत हैRectangle
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

मास्क प्राप्त करता है या सेट करता है[`Rectangle`](../../../aspose.psd/rectangle/)PSD फ़ाइल में लेयर मास्क का। यह बाएँ, दाएँ, ऊपर और नीचे के गुणों को लेता है और बनाता है[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### संपत्ति मूल्य

मुखौटा आयत।

### उदाहरण

यह उदाहरण दिखाता है कि Adobe® Photoshop® फ़ाइल में प्रोग्रामेटिक रूप से रास्टर लेयर मास्क कैसे प्राप्त करें, अपडेट करें, निकालें और जोड़ें।

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// बिग-एंडियन बाइट्स ऑर्डर में परिवर्तित इंट वैल्यू प्राप्त करें।
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// बड़े एंडियन से Int32 में परिवर्तित मान प्राप्त करें।
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// एक PSD छवि की परत से एक रेखापुंज मुखौटा प्राप्त करता है और इसे एक फ़ाइल में सहेजता है
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// फाइल से लेयर में एक रैस्टर मास्क जोड़ता है और इसे PSD फॉर्मेट इमेज सेव करता है
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // सिर्फ LayerMaskData जोड़ना सही बचत के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं होते हैं;
    // लेयर। लेयरमास्कडाटा = मास्क; // यह मास्क चैनल नहीं जोड़ता है

    // मास्क जोड़ें (या अपडेट करें)।
    layer.AddLayerMask(maskData); // लेकिन यह मास्क और चैनल दोनों को जोड़ता/अपडेट करता है!
}

// यह उदाहरण दिखाता है कि Adobe® Photoshop® फ़ाइल में प्रोग्रामेटिक रूप से रास्टर लेयर मास्क कैसे प्राप्त करें, अपडेट करें, निकालें और जोड़ें।
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // परत से रास्टर मास्क प्राप्त करें और इसे फ़ाइल में सहेजें
    SaveRasterMask("FourWithMasks2.msk", layer);

    // लेयर मास्क (इनवर्ट) बदलें और इमेज को सेव करें
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // सिर्फ LayerMaskData को बदलना रेंडरिंग को प्रभावित करने के लिए पर्याप्त है
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // लेकिन सिर्फ LayerMaskData को बदलना सही बचत के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं होते हैं;
    layer.LayerMaskData = mask; // यह या तो काम नहीं करता है
    layer.AddLayerMask(mask); // लेकिन यह मास्क और चैनल दोनों को अपडेट करता है!
    image.Save("FourWithMasksUpdated2.psd");

    // लेयर से रास्टर मास्क निकालें और इमेज को सेव करें
    layer.LayerMaskData = null; // केवल LayerMaskData को हटाना रेंडरिंग को प्रभावित करने के लिए पर्याप्त है, लेकिन PSD प्रारूप में सहेजने के लिए नहीं
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // लेकिन यह मास्क और मास्क चैनल दोनों को हटा देता है!
    image.Save("FourWithMasksRemoved2.psd");

    // फाइल से लेयर में रैस्टर मास्क जोड़ें और इमेज को सेव करें
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### यह सभी देखें

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* सभा [Aspose.PSD](../../../)


