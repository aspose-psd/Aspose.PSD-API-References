---
title: "क्लास SoLdResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoLdResource क्लास। यह SoLdResource क्लास को परिभाषित करता है जो PSD फ़ाइल में एक स्मार्ट ऑब्जेक्ट लेयर के बारे में जानकारी रखती है। यह Adobe Photoshop छवियों में स्मार्ट ऑब्जेक्ट लेयर्स का समर्थन करने के लिए उपयोग की जाती है।"
type: docs
weight: 3370
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---
{{< psd/tize >}}
## SoLdResource class

SoLdResource क्लास को परिभाषित करता है जो PSD फ़ाइल में एक स्मार्ट ऑब्जेक्ट लेयर के बारे में जानकारी रखती है। यह Adobe� Photoshop� छवियों में स्मार्ट ऑब्जेक्ट लेयर्स को समर्थन देने के लिए उपयोग किया जाता है।

```csharp
public class SoLdResource : SmartObjectResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SoLdResource](soldresource/#constructor)() | `SoLdResource` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। यह डिफ़ॉल्ट कंस्ट्रक्टर SoLdResourceLoader द्वारा उपयोग के लिए डिज़ाइन किया गया है। SoLdResource क्लास बनाने के लिए [`SmartResourceCreator`](../smartresourcecreator/) का उपयोग करें। |
| [SoLdResource](soldresource/#constructor_1)(Guid, bool, bool) | `SoLdResource` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। तैयार इंस्टेंस प्राप्त करने के लिए Items प्रॉपर्टी सेट करना या InitializeItems() को कॉल करना आवश्यक है। यह कंस्ट्रक्टर [`SmartResourceCreator`](../smartresourcecreator/) द्वारा उपयोग और यूनिट टेस्ट में उपयोग के लिए डिज़ाइन किया गया है। SoLdResource क्लास बनाने के लिए [`SmartResourceCreator`](../smartresourcecreator/) का उपयोग करें। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/antialiaspolicy/) { get; set; } | PSD छवि में स्मार्ट ऑब्जेक्ट लेयर डेटा की एंटी-एलियास नीति को प्राप्त करता है या सेट करता है। |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | PSD छवि में रखी गई लेयर के नीचे स्थान को प्राप्त करता है या सेट करता है। |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | PSD फ़ाइल में रखी गई लेयर की सीमाओं को प्राप्त करता है या सेट करता है। |
| [Comp](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/comp/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के कंप मान को प्राप्त करता है या सेट करता है। [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/compid/) { get; set; } | वर्तमान में चयनित कंप का ID प्राप्त करता है या सेट करता है चाइल्ड दस्तावेज़ के लिए, यदि कोई चयनित नहीं है तो यह -1 होगा। कंप पेज लेआउट की रचनाएँ हैं जिन्हें डिजाइनर बना सकते हैं। लेयर कंप्स का उपयोग करके, आप एक ही Adobe Photoshop फ़ाइल में लेआउट के कई संस्करण बना, प्रबंधित और देख सकते हैं। एक लेयर कंप लेयर्स पैनल की स्थिति का स्नैपशॉट है। लेयर कंप्स तीन प्रकार के लेयर विकल्पों को सहेजते हैं लेकिन यह प्रॉपर्टी PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर के लिए लेयर कंप चयन पहचानकर्ता प्राप्त करती है। [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Crop](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/crop/) { get; set; } | PSD छवि में स्मार्ट ऑब्जेक्ट लेयर डेटा की क्रॉप को प्राप्त करता है या सेट करता है। |
| [DurationDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationdenominator/) { get; set; } | अवधि हर (डिनॉमिनेटर) को प्राप्त करता है या सेट करता है। |
| [DurationNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/durationnumerator/) { get; set; } | अवधि अंश को प्राप्त करता है या सेट करता है। |
| [FrameCount](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framecount/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा की फ्रेम गिनती को प्राप्त करता है या सेट करता है। |
| [FrameStepDenominator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepdenominator/) { get; set; } | फ़्रेम स्टेप हर को प्राप्त करता है या सेट करता है। |
| [FrameStepNumerator](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/framestepnumerator/) { get; set; } | फ़्रेम स्टेप अंश को प्राप्त करता है या सेट करता है। |
| [Height](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/height/) { get; set; } | ऊँचाई को प्राप्त करता है या सेट करता है। |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | क्षैतिज मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | इस उदाहरण के वार्प शैली कस्टम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true है तो इसमें मेष बिंदु होते हैं। यदि false सेट किया जाता है तो मेष बिंदु मिटा दिए जाते हैं। |
| override [Items](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/items/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के डिस्क्रिप्टर आइटम्स को प्राप्त करता है या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | PSD फ़ाइल में रखी गई लेयर के बाएँ स्थान को प्राप्त करता है या सेट करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/length/) { get; } | स्मार्ट ऑब्जेक्ट संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| [NonAffineTransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/nonaffinetransformmatrix/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के नॉन‑अफ़ाइन ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/originalcompid/) { get; } | चाइल्ड दस्तावेज़ के लिए वर्तमान में चयनित Comp का मूल ID प्राप्त करता है, यदि कोई चयनित नहीं है तो यह -1 होगा। यह प्रॉपर्टी PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर के लिए मूल लेयर Comp चयन पहचानकर्ता प्राप्त करती है। [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| override [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/pagenumber/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा का पेज नंबर प्राप्त करता है या सेट करता है। |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | PSD फ़ाइल में रखी गई लेयर के अन्य परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedid/) { get; set; } | PSD इमेज में इस स्मार्ट ऑब्जेक्ट लेयर डेटा की विशिष्ट पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| override [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/placedlayertype/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के प्रकार को प्राप्त करता है या सेट करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| [Resolution](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolution/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा का रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| [ResolutionUnit](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/resolutionunit/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा की रिज़ॉल्यूशन माप इकाई को प्राप्त करता है या सेट करता है। |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | PSD फ़ाइल में रखी गई लेयर के दाएँ स्थान को प्राप्त करता है या सेट करता है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | स्थापित लेयर की शीर्ष स्थिति को प्राप्त करता है या सेट करता है PSD छवि में। |
| override [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/totalpages/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा की कुल पेजों की संख्या को प्राप्त करता है या सेट करता है। |
| override [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/transformmatrix/) { get; set; } | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| override [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/uniqueid/) { get; set; } | PSD इमेज में स्मार्ट ऑब्जेक्ट लेयर डेटा [`SmartObjectResource`](../smartobjectresource/) का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त करता है या सेट करता है। |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | स्थापित लेयर के U क्रम मान को प्राप्त करता है या सेट करता है PSD फ़ाइल में। |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | स्थापित लेयर के वार्प मान को प्राप्त करता है या सेट करता है PSD छवि में। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | स्थापित लेयर का संस्करण प्राप्त करता है PSD फ़ाइल में, आमतौर पर 3। |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | ऊर्ध्वाधर मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | स्थापित लेयर के V क्रम मान को प्राप्त करता है या सेट करता है PSD फ़ाइल में। |
| [Width](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/width/) { get; set; } | चौड़ाई को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/save/)(StreamContainer, int) | स्मार्ट ऑब्जेक्ट संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/soldresource/typetoolkey/) | टाइप टूल जानकारी कुंजी: 'SoLd'। |

## उदाहरण

निम्नलिखित कोड SoLdResource रिसोर्स के समर्थन को दर्शाता है।

```csharp
[C#]

// यह उदाहरण दिखाता है कि PSD फ़ाइल के स्मार्ट ऑब्जेक्ट लेयर डेटा प्रॉपर्टीज़ को कैसे प्राप्त या सेट किया जाए।

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

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
var outputFilePath = "LayeredSmartObjects8bit2_output.psd";
var expectedValues = new object[]
{
    new object[]
    {
        true,
        "76f05a3b-7523-5e42-a1bb-27f4735bffa0",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        149d,
        310d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        310d,
        149d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "d3388655-19e4-9742-82f2-f553bb01046a",
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 0.0d, 0.0d, 0.0d,
            49.666666666666664d, 49.666666666666664d, 49.666666666666664d, 49.666666666666664d,
            99.333333333333329d, 99.333333333333329d, 99.333333333333329d, 99.333333333333329d,
            149, 149, 149, 149,
        },
    },
    new object[]
    {
        true,
        "cf0477a8-8f92-ac4f-9462-f78e26234851",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        721d,
        1280d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        1280d,
        721d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "625cc4b9-2c5f-344f-8636-03caf2bd3489",
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 0.0, 0.0, 0.0,
            240.33333333333331, 240.33333333333331, 240.33333333333331, 240.33333333333331,
            480.66666666666663, 480.66666666666663, 480.66666666666663, 480.66666666666663,
            721, 721, 721, 721,
        },
        0,
        0
    }
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    SoLdResource resource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            resource = imageResource as SoLdResource;
            if (resource != null)
            {
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[0], resource.IsCustom);
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
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
                AssertAreEqual((IEnumerable)expectedValue[30], resource.NonAffineTransformMatrix);
                if (resource.IsCustom)
                {
                    AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
                    AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
                    var temp = resource.VerticalMeshPoints;
                    resource.VerticalMeshPoints = resource.HorizontalMeshPoints;
                    resource.HorizontalMeshPoints = temp;
                }

                // इन मानों को PlLdResource (निर्दिष्ट UniqueId के साथ) में भी बदलना चाहिए।
                // और उनमें से कुछ को LinkDataSource में अंडरलाइनिंग स्मार्ट ऑब्जेक्ट के अनुरूप होना चाहिए।
                resource.PageNumber = 2;
                resource.TotalPages = 3;
                resource.AntiAliasPolicy = 0;
                resource.Value = 1.23456789;
                resource.Perspective = 0.123456789;
                resource.PerspectiveOther = 0.987654321;
                resource.Top = -126;
                resource.Left = -215;
                resource.Bottom = 248;
                resource.Right = 145;
                resource.Crop = 4;
                resource.FrameStepNumerator = 1;
                resource.FrameStepDenominator = 601;
                resource.DurationNumerator = 2;
                resource.DurationDenominator = 602;
                resource.FrameCount = 11;
                resource.Width = 541;
                resource.Height = 249;
                resource.Resolution = 144;
                resource.Comp = 21;
                resource.CompId = 22;
                resource.TransformMatrix = new double[8]
                {
                    12.937922786050663,
                    19.419959734187131,
                    2.85445817782261,
                    1.0540625423957124,
                    7.20861031651307,
                    14.634102808208553,
                    17.292074924741144,
                    4
                };
                resource.NonAffineTransformMatrix = new double[8]
                {
                    129.937922786050663,
                    195.419959734187131,
                    26.85445817782261,
                    12.0540625423957124,
                    72.20861031651307,
                    147.634102808208553,
                    175.292074924741144,
                    42
                };

                // यदि कोई रेफ़रेंस है तो इस यूनिक आईडी को बदलना चाहिए।
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

                // कुछ पैरामीटर्स के साथ सावधान रहें: इमेज Adobe® Photoshop® द्वारा अपठनीय हो सकती है।
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // इसे न बदलें, अन्यथा 
 आप फ्री ट्रांसफ़ॉर्म का उपयोग नहीं कर पाएंगे।
                // या 
 अंडरलाइनिंग स्मार्ट ऑब्जेक्ट को वेक्टर टाइप में बदलें।
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // इस यूनिक आईडी के साथ एक वैध PlLdResource होना चाहिए।
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### देखें भी

* class [SmartObjectResource](../smartobjectresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


