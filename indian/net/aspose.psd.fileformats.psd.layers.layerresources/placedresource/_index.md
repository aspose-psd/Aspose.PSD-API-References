---
title: Class PlacedResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PlacedResource कक्ष. प्लेस्ड रसर्स क्लस क परभषत करत है जसमें PSD फ़इल में रख गई परत य स्मर्ट ऑब्जेक्ट परत के बरे में समन्य जनकर हत है क उपयग Adobe Photoshop छवयं में स्मर्ट ऑब्जेक्ट परतं क समर्थन करने के लए कय जत है
type: docs
weight: 2940
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---
## PlacedResource class

प्लेस्ड रिसोर्स क्लास को परिभाषित करता है जिसमें PSD फ़ाइल में रखी गई परत या स्मार्ट ऑब्जेक्ट परत के बारे में सामान्य जानकारी होती है। का उपयोग Adobe® Photoshop® छवियों में स्मार्ट ऑब्जेक्ट परतों का समर्थन करने के लिए किया जाता है।

```csharp
public abstract class PlacedResource : LayerResource, IPlacedLayerResource
```

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/antialiaspolicy/) { get; set; } | PSD छवि में रखी गई परत की अन्य उपनाम नीति को प्राप्त या सेट करता है। |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | PSD छवि में रखी परत के निचले स्थान को प्राप्त या सेट करता है। |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | PSD फ़ाइल में रखी परत की सीमा प्राप्त या सेट करता है। |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | PSD फ़ाइल में रखी गई परत के क्षैतिज जाल बिंदुओं को प्राप्त या सेट करता है। |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | क्षैतिज जाल बिंदुओं की माप इकाई प्राप्त या सेट करता है। |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि क्या यह उदाहरण ताना शैली कस्टम है। यदि सही है तो इसमें जाल बिंदु शामिल हैं। अगर असत्य पर सेट किया जाता है तो यह जाली बिंदुओं को मिटा देता है. |
| virtual [Items](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/items/) { get; set; } | ताना आइटम प्राप्त या सेट करता है। |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | परत संसाधन कुंजी प्राप्त करता है. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | PSD फ़ाइल में रखी गई परत के बाएं स्थान को प्राप्त या सेट करता है। |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | बाइट्स में परत संसाधन लंबाई प्राप्त करता है। |
| virtual [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/pagenumber/) { get; set; } | PSD फ़ाइल में रखी गई परत की पृष्ठ संख्या प्राप्त या सेट करता है। |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | PSD फ़ाइल में रखी गई परत का परिप्रेक्ष्य मान प्राप्त या सेट करता है। |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | PSD फ़ाइल में रखी गई परत के परिप्रेक्ष्य को अन्य मान देता है या सेट करता है। |
| virtual [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/placedlayertype/) { get; set; } | PSD फ़ाइल में रखी गई परत के प्रकार को प्राप्त या सेट करता है। |
| abstract [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | परत संसाधन के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 कोई प्रतिबंध नहीं दर्शाता है। |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | PSD फ़ाइल में रखी गई परत का सही स्थान प्राप्त या सेट करता है। |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/signature/) { get; } | प्लेस्ड रिसोर्स सिग्नेचर प्राप्त करता है। |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | PSD छवि में रखी परत के शीर्ष स्थान को प्राप्त या सेट करता है। |
| virtual [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/totalpages/) { get; set; } | PSD फ़ाइल में रखी गई परत के कुल पृष्ठों को प्राप्त या सेट करता है। |
| virtual [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/transformmatrix/) { get; set; } | PSD फ़ाइल में रखी गई परत के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त या सेट करता है। |
| virtual [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uniqueid/) { get; set; } | PSD छवि में रखी गई परत का वैश्विक अद्वितीय पहचानकर्ता प्राप्त या सेट करता है। |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | PSD फ़ाइल में रखी गई परत का यू ऑर्डर मान प्राप्त या सेट करता है। |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | PSD छवि में रखी गई परत का ताना मान प्राप्त करता है या सेट करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | PSD फ़ाइल में रखी गई परत का संस्करण प्राप्त करता है, आमतौर पर 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | PSD फ़ाइल में रखी गई परत के क्षैतिज जाल बिंदुओं को प्राप्त या सेट करता है। |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | ऊर्ध्वाधर जाल बिंदुओं की माप इकाई प्राप्त या सेट करता है। |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | PSD फ़ाइल में रखी परत का V क्रम मान प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| abstract [Save](../../aspose.psd.fileformats.psd.layers/layerresource/save/)(StreamContainer, int) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

### उदाहरण

निम्न कोड SoLEResource, SmartObjectResource और PlacedResource संसाधनों के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

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

void CheckSmartObjectResourceValues(object[] expectedValue, SmartObjectResource resource)
{
    AssertAreEqual(expectedValue[0], resource.IsCustom);
    AssertAreEqual(expectedValue[2], resource.PageNumber);
    AssertAreEqual(expectedValue[3], resource.TotalPages);
    AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
    AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
    AssertAreEqual(8, resource.TransformMatrix.Length);
    AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
    AssertAreEqual(expectedValue[7], resource.Value);
    AssertAreEqual(expectedValue[8], resource.Perspective);
    AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
    AssertAreEqual(expectedValue[10], resource.Top);
    AssertAreEqual(expectedValue[11], resource.Left);
    AssertAreEqual(expectedValue[12], resource.Bottom);
    AssertAreEqual(expectedValue[13], resource.Right);
    AssertAreEqual(expectedValue[14], resource.UOrder);
    AssertAreEqual(expectedValue[15], resource.VOrder);

    AssertAreEqual(expectedValue[16], resource.Crop);
    AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
    AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
    AssertAreEqual(expectedValue[19], resource.DurationNumerator);
    AssertAreEqual(expectedValue[20], resource.DurationDenominator);
    AssertAreEqual(expectedValue[21], resource.FrameCount);
    AssertAreEqual(expectedValue[22], resource.Width);
    AssertAreEqual(expectedValue[23], resource.Height);
    AssertAreEqual(expectedValue[24], resource.Resolution);
    AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
    AssertAreEqual(expectedValue[26], resource.Comp);
    AssertAreEqual(expectedValue[27], resource.CompId);
    AssertAreEqual(expectedValue[28], resource.OriginalCompId);
    AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
    AssertAreEqual(expectedValue[30], resource.NonAffineTransformMatrix);
    if (resource.IsCustom)
    {
        AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
        AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
        AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
    }
}

void SetNewSmartValues(SmartObjectResource resource, object[] newValues)
{
    // यह मान हम संसाधन में नहीं बदलते हैं
    newValues[0] = resource.IsCustom;
    newValues[1] = resource.UniqueId.ToString();
    newValues[5] = resource.PlacedLayerType;
    newValues[14] = resource.UOrder;
    newValues[15] = resource.VOrder;
    newValues[28] = resource.OriginalCompId;

    // यह मान PlLdResource (निर्दिष्ट UniqueId के साथ) में भी बदला जाना चाहिए
    // और उनमें से कुछ को LinkDataSource में अंडरलाइनिंग स्मार्ट ऑब्जेक्ट के अनुरूप होना चाहिए
    resource.PageNumber = (int)newValues[2]; // 2;
    resource.TotalPages = (int)newValues[3]; // 3;
    resource.AntiAliasPolicy = (int)newValues[4]; // 0;
    resource.TransformMatrix = (double[])newValues[6];
    resource.Value = (double)newValues[7]; // 1.23456789;
    resource.Perspective = (double)newValues[8]; // 0.123456789;
    resource.PerspectiveOther = (double)newValues[9]; // 0.987654321;
    resource.Top = (double)newValues[10]; // -126;
    resource.Left = (double)newValues[11]; // -215;
    resource.Bottom = (double)newValues[12]; // 248;
    resource.Right = (double)newValues[13]; // 145;
    resource.Crop = (int)newValues[16]; // 5;
    resource.FrameStepNumerator = (int)newValues[17]; // 1;
    resource.FrameStepDenominator = (int)newValues[18]; // 601;
    resource.DurationNumerator = (int)newValues[19]; // 2;
    resource.DurationDenominator = (int)newValues[20]; // 602;
    resource.FrameCount = (int)newValues[21]; // 11;
    resource.Width = (double)newValues[22]; // 541;
    resource.Height = (double)newValues[23]; // 249;
    resource.Resolution = (double)newValues[24]; // 144;
    resource.ResolutionUnit = (UnitTypes)newValues[25];
    resource.Comp = (int)newValues[26]; // 21;
    resource.CompId = (int)newValues[27]; // 22;
    resource.NonAffineTransformMatrix = (double[])newValues[30];

    // इस अनूठी आईडी को संदर्भों में बदला जाना चाहिए यदि कोई हो
    resource.PlacedId = new Guid((string)newValues[29]);  // "12345678-9abc-def0-9876-54321fecba98");
    if (resource.IsCustom)
    {
        resource.HorizontalMeshPointUnit = (UnitTypes)newValues[31];
        resource.HorizontalMeshPoints = (double[])newValues[32];
        resource.VerticalMeshPointUnit = (UnitTypes)newValues[33];
        resource.VerticalMeshPoints = (double[])newValues[34];
    }

    // कुछ मापदंडों से सावधान रहें: सहेजी गई छवि Adobe® Photoshop® द्वारा अपठनीय हो सकती है
    ////resource.UOrder = 6;
    ////संसाधन। VOrder = 9;

    // इसे कोई परिवर्तन न करें अन्यथा आप निःशुल्क रूपांतरण का उपयोग नहीं कर पाएंगे
    // या अंडरलाइनिंग स्मार्ट ऑब्जेक्ट को वेक्टर प्रकार में बदलें
    ////resource.PlacedLayerType = PlacedLayerType.Vector;

    // इस विशिष्ट आईडी के साथ मान्य PlLdResource होना चाहिए
    ////resource.UniqueId = नया गाइड ("98765432-10fe-cba0-1234-56789abcdef0");
}

object[] newSmartValues = new object[]
{
    true,
    null,
    2,
    3,
    0,
    PlacedLayerType.ImageStack,
    new double[8]
    {
        12.937922786050663,
        19.419959734187131,
        2.85445817782261,
        1.0540625423957124,
        7.20861031651307,
        14.634102808208553,
        17.292074924741144,
        4
    },
    1.23456789,
    0.123456789,
    0.987654321,
    -126d,
    -215d,
    248d,
    145d,
    4,
    4,
    5,
    1,
    601,
    2,
    602,
    11,
    541d,
    249d,
    144d,
    UnitTypes.Percent,
    21,
    22,
    23,
    "12345678-9abc-def0-9876-54321fecba98",
    new double[8]
    {
        129.937922786050663,
        195.419959734187131,
        26.85445817782261,
        12.0540625423957124,
        72.20861031651307,
        147.634102808208553,
        175.292074924741144,
        42
    },
    UnitTypes.Points,
    new double[16]
    {
        0.01d, 103.33333333333433d, 206.66686666666666d, 310.02d,
        0.20d, 103.33333333333533d, 206.69666666666666d, 310.03d,
        30.06d, 103.33333333336333d, 206.66660666666666d, 310.04d,
        04.05d, 103.33333333373333d, 206.66666166666666d, 310.05d
    },
    UnitTypes.Distance,
    new double[16]
    {
        0.06d, 0.07d, 0.08d, 0.09d,
        49.066666666666664d, 49.266666666666664d, 49.566666666666664d, 49.766666666666664d,
        99.133333333333329d, 99.433333333333329d, 99.633333333333329d, 99.833333333333329d,
        140, 141, 142, 143,
    },
};

object[] expectedValues = new object[]
{
    new object[]
    {
        false,
        "5867318f-3174-9f41-abca-22f56a75247e",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
        0d,
        0d,
        0d,
        0d,
        0d,
        2d,
        2d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        2d,
        2d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "64b3997c-06e0-be40-a349-41acf397c897",
        new double[8]
        {
            0, 0, 2, 0, 2, 2, 0, 2
        },
    }
};

var sourceFilePath = "rgb8_2x2_linked.psd";
var outputPath = "rgb8_2x2_linked_output.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLeResource soleResource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as SoLeResource;
            if (resource != null)
            {
                soleResource = resource;
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                CheckSmartObjectResourceValues(expectedValue, resource);
                SetNewSmartValues(resource, newSmartValues);

                break;
            }
        }
    }

    AssertIsTrue(soleResource != null);
    image.Save(outputPath, new PsdOptions(image));
    using (PsdImage savedImage = (PsdImage)Image.Load(outputPath))
    {
        foreach (Layer imageLayer in savedImage.Layers)
        {
            foreach (var imageResource in imageLayer.Resources)
            {
                var resource = imageResource as SoLeResource;
                if (resource != null)
                {
                    CheckSmartObjectResourceValues(newSmartValues, resource);

                    break;
                }
            }
        }
    }
}
```

### यह सभी देखें

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IPlacedLayerResource](../iplacedlayerresource/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


