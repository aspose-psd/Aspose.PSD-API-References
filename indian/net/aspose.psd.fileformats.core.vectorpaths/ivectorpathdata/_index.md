---
title: "इंटरफ़ेस IVectorPathData"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData इंटरफ़ेस। वेक्टर पाथ डेटा तक पहुँच के लिए इंटरफ़ेस"
type: docs
weight: 1360
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

वेक्टर पाथ डेटा तक पहुंच के लिए इंटरफ़ेस।

```csharp
public interface IVectorPathData
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | इस इंस्टेंस के निष्क्रिय होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | इस इंस्टेंस के उल्टे होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | इस इंस्टेंस के न जुड़े होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | पाथ रिकॉर्ड्स को प्राप्त करता है या सेट करता है। |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | संस्करण को प्राप्त करता है या सेट करता है। |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


