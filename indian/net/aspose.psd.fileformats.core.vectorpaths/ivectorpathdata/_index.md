---
title: Interface IVectorPathData
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData इंटरफेस. वेक्टर पथ डेट तक पहुंच के लए इंटरफ़ेस
type: docs
weight: 1350
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

वेक्टर पथ डेटा तक पहुंच के लिए इंटरफ़ेस।

```csharp
public interface IVectorPathData
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण अक्षम है या नहीं। |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण उल्टा है। |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण लिंक नहीं है। |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | पथ रिकॉर्ड प्राप्त या सेट करता है। |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | संस्करण प्राप्त या सेट करता है। |

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

* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* सभा [Aspose.PSD](../../)


