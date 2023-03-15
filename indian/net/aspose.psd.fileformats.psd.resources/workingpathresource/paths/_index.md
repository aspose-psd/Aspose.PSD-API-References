---
title: WorkingPathResource.Paths
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: WorkingPathResource संपत्त. पथ रकर्ड प्रप्त य सेट करत है
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.resources/workingpathresource/paths/
---
## WorkingPathResource.Paths property

पथ रिकॉर्ड प्राप्त या सेट करता है।

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### संपत्ति मूल्य

पथ।

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

* class [VectorPathRecord](../../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/)
* class [WorkingPathResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* सभा [Aspose.PSD](../../../)


