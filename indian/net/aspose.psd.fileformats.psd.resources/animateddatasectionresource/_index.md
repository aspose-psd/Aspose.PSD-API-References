---
title: Class AnimatedDataSectionResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Resources.AnimatedDataSectionResource कक्ष. एनमेटेड डेट अनुभग प्लगइन संसधन
type: docs
weight: 3630
url: /hi/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---
## AnimatedDataSectionResource class

एनिमेटेड डेटा अनुभाग प्लग-इन संसाधन।

```csharp
public class AnimatedDataSectionResource : ResourceBlock
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AnimatedDataSection](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/) { get; } | एनिमेटेड डेटा अनुभाग संरचना प्राप्त या सेट करता है। |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/datasize/) { get; } | बाइट्स में संसाधन डेटा आकार प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त या सेट करता है। |
| [KeyName](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/keyname/) { get; } | संसाधन कुंजी नाम. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/minimalversion/) { get; } | न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम प्राप्त या सेट करता है। पास्कल स्ट्रिंग, आकार को समान बनाने के लिए गद्देदार (शून्य नाम में 0 के दो बाइट होते हैं). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | अपने डेटा सहित बाइट्स में संसाधन ब्लॉक आकार प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | संसाधन ब्लॉक को निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों की पुष्टि करता है. |

### उदाहरण

निम्न कोड प्रदर्शित करता है कि एनिमेटेड डेटा के टाइमलाइन फ्रेम में विलंब समय को कैसे सेट/अपडेट किया जाए।

```csharp
[C#]

string sourceFile = "3_animated.psd";
string outputPsd = "output_3_animated.psd";

T FindStructure<T>(IEnumerable<OSTypeStructure> structures, string keyName) where T : OSTypeStructure
{
    foreach (var structure in structures)
    {
        if (structure.KeyName.ClassName == keyName)
        {
            return structure as T;
        }
    }

    return null;
}

OSTypeStructure[] AddOrReplaceStructure(IEnumerable<OSTypeStructure> structures, OSTypeStructure newStructure)
{
    List<OSTypeStructure> listOfStructures = new List<OSTypeStructure>(structures);

    for (int i = 0; i < listOfStructures.Count; i++)
    {
        OSTypeStructure structure = listOfStructures[i];
        if (structure.KeyName.ClassName == newStructure.KeyName.ClassName)
        {
            listOfStructures.RemoveAt(i);
            break;
        }
    }

    listOfStructures.Add(newStructure);

    return listOfStructures.ToArray();
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var imageResource in image.ImageResources)
    {
        if (imageResource is AnimatedDataSectionResource)
        {
            var animatedData =
                (AnimatedDataSectionStructure) (imageResource as AnimatedDataSectionResource).AnimatedDataSection;
            var framesList = FindStructure<ListStructure>(animatedData.Items, "FrIn");

            var frame1 = (DescriptorStructure)framesList.Types[1];

            // 100 सेंटी-सेकंड मान के साथ फ़्रेम विलंब रिकॉर्ड बनाता है जो 1 सेकंड के बराबर है।
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // सेंटी-सेकंड में समय निर्धारित करें।

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### यह सभी देखें

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* सभा [Aspose.PSD](../../)


