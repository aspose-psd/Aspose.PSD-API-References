---
title: "WorkingPathResource.WorkingPathResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "WorkingPathResource कंस्ट्रक्टर। WorkingPathResource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource constructor

[`WorkingPathResource`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| dataBytes | Byte[] | वेक्टर पाथ का डेटा। |

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

* class [WorkingPathResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


