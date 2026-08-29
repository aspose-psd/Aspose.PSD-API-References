---
title: "क्लास WorkingPathResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource क्लास। कार्य पथ संसाधन"
type: docs
weight: 4450
url: /hi/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource class

कार्य पथ संसाधन।

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | `WorkingPathResource` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | संसाधन डेटा आकार को बाइट्स में प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | इस इंस्टेंस के निष्क्रिय होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | इस इंस्टेंस के उल्टे होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | इस इंस्टेंस के न जुड़े होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम को प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट्स 0 से बना होता है)। |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | पाथ रिकॉर्ड्स को प्राप्त करता है या सेट करता है। |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर को प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | डेटा सहित संसाधन ब्लॉक आकार को बाइट्स में प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | संस्करण को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों को मान्य करता है। |

## उदाहरण

यह उदाहरण PsdImage.ImageResources में 'WorkingPathResource' संसाधन के समर्थन को दर्शाता है ताकि Crop ऑपरेशन सही ढंग से काम करे।

```csharp
[C#]

// इमेज को क्रॉप करें और सहेजें।
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // WorkingPathResource संसाधन खोजें।
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

    // क्रॉप करें और सहेजें।
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// सहेजी गई इमेज लोड करें और बदलावों की जाँच करें।
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // WorkingPathResource संसाधन खोजें।
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

### देखें भी

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


