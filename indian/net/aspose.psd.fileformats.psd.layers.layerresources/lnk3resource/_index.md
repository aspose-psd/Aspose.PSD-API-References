---
title: "क्लास Lnk3Resource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk3Resource क्लास। वह क्लास परिभाषित करता है जो PSD फ़ॉर्मेट 32 बिट प्रति चैनल इमेज में एम्बेडेड फ़ाइल के बारे में जानकारी रखती है। लिंक रिसोर्स में कई LiFdDataSource इंस्टेंस हो सकते हैं जिन्हें इंडेक्सर द्वारा एक्सेस किया जा सकता है।"
type: docs
weight: 3040
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---
{{< psd/tize >}}
## Lnk3Resource class

PSD फ़ॉर्मेट 32 बिट प्रति चैनल इमेज में एम्बेडेड फ़ाइल के बारे में जानकारी रखने वाली क्लास को परिभाषित करता है। लिंक रिसोर्स में कई [`LiFdDataSource`](../lifddatasource/) इंस्टेंस हो सकते हैं जिन्हें इंडेक्सर द्वारा एक्सेस किया जा सकता है।

```csharp
public class Lnk3Resource : Lnk2Resource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Lnk3Resource](lnk3resource/)() | `Lnk3Resource` क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | इंडेक्सर द्वारा एक्सेस किए जा सकने वाले लिंक डेटा स्रोतों की संख्या प्राप्त करता है। |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | यह दर्शाने वाला मान प्राप्त करता है कि यह लिंक रिसोर्स इंस्टेंस खाली है या नहीं। |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | निर्दिष्ट इंडेक्स पर स्थित [`LiFdDataSource`](../lifddatasource/) प्राप्त करता है। (2 इंडेक्सर) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD ग्लोबल लिंक रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | रिसोर्स ब्लॉक डेटा को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

## उदाहरण

यह उदाहरण दिखाता है कि Lnk2Resource और Lnk3Resource की प्रॉपर्टीज़ को कैसे प्राप्त और सेट किया जाए।

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

object[] Lnk2ResourceSupportCases = new object[]
{
    new object[]
    {
        "00af34a0-a90b-674d-a821-73ee508c5479",
        "rgb8_2x2.png",
        "png",
        string.Empty,
        0x53,
        0d,
        string.Empty,
        7,
        true,
        0x124L,
        0x74cL
    }
};

object[] LayeredLnk2ResourceSupportCases = new object[]
{
    new object[]
    {
        "69ac1c0d-1b74-fd49-9c7e-34a7aa6299ef",
        "huset.jpg",
        "JPEG",
        string.Empty,
        0x9d46,
        0d,
        "xmp.did:0F94B342065B11E395B1FD506DED6B07",
        7,
        true,
        0x9E60L,
        0xc60cL
    },
    new object[]
    {
        "5a7d1965-0eae-b24e-a82f-98c7646424c2",
        "panama-papers.jpg",
        "JPEG",
        string.Empty,
        0xF56B,
        0d,
        "xmp.did:BDE940CBF51B11E59D759CDA690663E3",
        7,
        true,
        0xF694L,
        0x10dd4L
    },
};

object[] LayeredLnk3ResourceSupportCases = new object[]
{
    new object[]
    {
        "2fd7ba52-0221-de4c-bdc4-1210580c6caa",
        "panama-papers.jpg",
        "JPEG",
        string.Empty,
        0xF56B,
        0d,
        "xmp.did:BDE940CBF51B11E59D759CDA690663E3",
        7,
        true,
        0xF694l,
        0x10dd4L
    },
    new object[]
    {
        "372d52eb-5825-8743-81a7-b6f32d51323d",
        "huset.jpg",
        "JPEG",
        string.Empty,
        0x9d46,
        0d,
        "xmp.did:0F94B342065B11E395B1FD506DED6B07",
        7,
        true,
        0x9E60L,
        0xc60cL
    },
};

var basePath = "" + Path.DirectorySeparatorChar;
string Output = "output" + Path.DirectorySeparatorChar;

// PSD फ़ाइल में एक स्मार्ट ऑब्जेक्ट का डेटा फ़ाइल में सहेजता है।
void SaveSmartObjectData(string prefix, string fileName, byte[] data)
{
    var filePath = basePath + prefix + "_" + fileName;

    using (var container = FileStreamContainer.CreateFileStream(filePath, false))
    {
        container.Write(data);
    }
}

// PSD फ़ाइल में एक स्मार्ट ऑब्जेक्ट के लिए नया डेटा लोड करता है।
byte[] LoadNewData(string fileName)
{
    using (var container = FileStreamContainer.OpenFileStream(basePath + fileName))
    {
        return container.ToBytes();
    }
}

// PSD इमेज में PSD Lnk2 / Lnk3 रिसोर्स और उसके liFD डेटा स्रोतों की प्रॉपर्टीज़ को प्राप्त और सेट करता है।
void ExampleOfLnk2ResourceSupport(
    string fileName,
    int dataSourceCount,
    int length,
    int newLength,
    object[] dataSourceExpectedValues)
{
    using (PsdImage image = (PsdImage)Image.Load(basePath + fileName))
    {
        Lnk2Resource lnk2Resource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnk2Resource = resource as Lnk2Resource;
            if (lnk2Resource != null)
            {
                AssertAreEqual(lnk2Resource.DataSourceCount, dataSourceCount);
                AssertAreEqual(lnk2Resource.Length, length);
                AssertAreEqual(lnk2Resource.IsEmpty, false);

                for (int i = 0; i < lnk2Resource.DataSourceCount; i++)
                {
                    LiFdDataSource lifdSource = lnk2Resource[i];
                    object[] expected = (object[])dataSourceExpectedValues[i];
                    AssertAreEqual(LinkDataSourceType.liFD, lifdSource.Type);
                    AssertAreEqual(new Guid((string)expected[0]), lifdSource.UniqueId);
                    AssertAreEqual(expected[1], lifdSource.OriginalFileName);
                    AssertAreEqual(expected[2], lifdSource.FileType.TrimEnd(' '));
                    AssertAreEqual(expected[3], lifdSource.FileCreator.TrimEnd(' '));
                    AssertAreEqual(expected[4], lifdSource.Data.Length);
                    AssertAreEqual(expected[5], lifdSource.AssetModTime);
                    AssertAreEqual(expected[6], lifdSource.ChildDocId);
                    AssertAreEqual(expected[7], lifdSource.Version);
                    AssertAreEqual((bool)expected[8], lifdSource.HasFileOpenDescriptor);
                    AssertAreEqual(expected[9], lifdSource.Length);

                    if (lifdSource.HasFileOpenDescriptor)
                    {
                        AssertAreEqual(-1, lifdSource.CompId);
                        AssertAreEqual(-1, lifdSource.OriginalCompId);
                        lifdSource.CompId = int.MaxValue;
                    }

                    SaveSmartObjectData(
                        Output + fileName,
                        lifdSource.OriginalFileName,
                        lifdSource.Data);
                    lifdSource.Data = LoadNewData("new_" + lifdSource.OriginalFileName);
                    AssertAreEqual(expected[10], lifdSource.Length);

                    lifdSource.ChildDocId = Guid.NewGuid().ToString();
                    lifdSource.AssetModTime = double.MaxValue;
                    lifdSource.FileType = "test";
                    lifdSource.FileCreator = "me";
                }

                AssertAreEqual(newLength, lnk2Resource.Length);
                break;
            }
        }

        AssertAreEqual(true, lnk2Resource != null);
        if (image.BitsPerChannel < 32) // 32 bit per channel saving is not supported yet
        {
            image.Save(basePath + Output + fileName, new PsdOptions(image));
        }
    }
}

// यह उदाहरण दिखाता है कि 8 बिट प्रति चैनल के लिए PSD Lnk2 रिसोर्स और उसके liFD डेटा स्रोतों की प्रॉपर्टीज़ को कैसे प्राप्त और सेट किया जाए।
ExampleOfLnk2ResourceSupport("rgb8_2x2_embedded_png.psd", 1, 0x12C, 0x0000079c, Lnk2ResourceSupportCases);

// यह उदाहरण दिखाता है कि 32 बिट प्रति चैनल के लिए PSD Lnk3 रिसोर्स और उसके liFD डेटा स्रोतों की प्रॉपर्टीज़ को कैसे प्राप्त और सेट किया जाए।
ExampleOfLnk2ResourceSupport("Layered PSD file smart objects.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk3ResourceSupportCases);

// यह उदाहरण दिखाता है कि 16 बिट प्रति चैनल के लिए PSD Lnk2 रिसोर्स और उसके liFD डेटा स्रोतों की प्रॉपर्टीज़ को कैसे प्राप्त और सेट किया जाए।
ExampleOfLnk2ResourceSupport("LayeredSmartObjects16bit.psd", 2, 0x19504, 0x0001d3e0, LayeredLnk2ResourceSupportCases);
```

### देखें भी

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* class [Lnk2Resource](../lnk2resource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


