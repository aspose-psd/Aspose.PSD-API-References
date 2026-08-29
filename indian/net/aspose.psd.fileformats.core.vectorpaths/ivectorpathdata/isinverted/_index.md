---
title: "IVectorPathData.IsInverted"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IVectorPathData प्रॉपर्टी। एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि यह इंस्टेंस उल्टा है या नहीं"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/
---
{{< psd/tize >}}
## IVectorPathData.IsInverted property

इस इंस्टेंस के उल्टे होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है।

```csharp
public bool IsInverted { get; set; }
```

### Property Value

`true` यदि यह इंस्टेंस उलटा है; अन्यथा, `false`.

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

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


