---
title: Class WorkingPathResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource कक्ष. कर्य पथ संसधन.
type: docs
weight: 3980
url: /hi/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

कार्य पथ संसाधन.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | का एक नया उदाहरण प्रारंभ करता है`WorkingPathResource` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | बाइट्स में संसाधन डेटा आकार प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त या सेट करता है। |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण अक्षम है या नहीं। |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण उल्टा है। |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण लिंक नहीं है। |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम प्राप्त या सेट करता है। पास्कल स्ट्रिंग, आकार को समान बनाने के लिए गद्देदार (शून्य नाम में 0 के दो बाइट होते हैं). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | पथ रिकॉर्ड प्राप्त या सेट करता है। |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | अपने डेटा सहित बाइट्स में संसाधन ब्लॉक आकार प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | संस्करण प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | संसाधन ब्लॉक को निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों की पुष्टि करता है. |

### उदाहरण

यह उदाहरण फसल संचालन के सही कार्य के लिए PsdImage.ImageResources में 'WorkingPathResource' संसाधन के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

// क्रॉप इमेज और सेव करें।
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // वर्किंगपाथ रिसोर्स संसाधन खोजें।
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // फसल और बचाओ।
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// सहेजी गई छवि लोड करें और परिवर्तनों की जांच करें।
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // वर्किंगपाथ रिसोर्स संसाधन खोजें।
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### यह सभी देखें

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* सभा [Aspose.PSD](../../)


