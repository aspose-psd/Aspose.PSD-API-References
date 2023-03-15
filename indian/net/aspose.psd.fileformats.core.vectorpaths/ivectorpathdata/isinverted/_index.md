---
title: IVectorPathData.IsInverted
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: IVectorPathData संपत्त. एक मन प्रप्त करत है य सेट करत है ज दर्शत है क यह उदहरण उल्ट है
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/
---
## IVectorPathData.IsInverted property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण उल्टा है।

```csharp
public bool IsInverted { get; set; }
```

### संपत्ति मूल्य

`सत्य` यदि यह उदाहरण उलटा है; अन्यथा,`असत्य` .

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

* interface [IVectorPathData](../)
* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* सभा [Aspose.PSD](../../../)


