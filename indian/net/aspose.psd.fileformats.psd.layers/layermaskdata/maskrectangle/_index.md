---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerMaskData प्रॉपर्टी। PSD फ़ाइल में लेयर मास्क के मास्क Rectangle को प्राप्त करता है या सेट करता है। यह बाएँ, दाएँ, ऊपर और नीचे की प्रॉपर्टीज़ लेता है और Rectangle बनाता है"
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

मास्क [`Rectangle`](../../../aspose.psd/rectangle/) को प्राप्त करता है या सेट करता है, जो PSD फ़ाइल में लेयर मास्क का है। यह बाएँ, दाएँ, ऊपर और नीचे की प्रॉपर्टीज़ लेता है और [`Rectangle`](../../../aspose.psd/rectangle/) बनाता है

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

मास्क Rectangle।

## उदाहरण

यह उदाहरण दिखाता है कि Adobe® Photoshop® फ़ाइल में रास्टर लेयर मास्क को प्रोग्रामेटिक रूप से कैसे प्राप्त करें, अपडेट करें, हटाएँ और जोड़ें।

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

// int मान को बिग-एंडियन बाइट क्रम में परिवर्तित करके प्राप्त करता है।
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// बिग-एंडियन से Int32 में परिवर्तित मान को प्राप्त करता है।
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

// PSD इमेज की लेयर से रास्टर मास्क प्राप्त करता है और उसे फ़ाइल में सहेजता है
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

// फ़ाइल से रास्टर मास्क को लेयर में जोड़ता है और उसे PSD फ़ॉर्मेट इमेज में सहेजता है
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

    // केवल LayerMaskData जोड़ना सही सहेजने के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं किए गए हैं;
    // layer.LayerMaskData = mask; // यह मास्क चैनल नहीं जोड़ता है

    // मास्क जोड़ें (या अपडेट करें)
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// यह उदाहरण दिखाता है कि Adobe® Photoshop® फ़ाइल में रास्टर लेयर मास्क को प्रोग्रामेटिक रूप से कैसे प्राप्त करें, अपडेट करें, हटाएँ और जोड़ें।
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // लेयर से रास्टर मास्क प्राप्त करें और उसे फ़ाइल में सहेजें
    SaveRasterMask("FourWithMasks2.msk", layer);

    // लेयर मास्क बदलें (इनवर्ट) और इमेज सहेजें
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // केवल LayerMaskData बदलना रेंडरिंग पर प्रभाव डालने के लिए पर्याप्त है
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // लेकिन केवल LayerMaskData बदलना सही सहेजने के लिए पर्याप्त नहीं है क्योंकि चैनल अपडेट नहीं किए गए हैं;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // लेयर से रास्टर मास्क हटाएँ और इमेज सहेजें
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // फ़ाइल से रास्टर मास्क को लेयर में जोड़ें और इमेज सहेजें
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### देखें भी

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


