---
title: "क्लास BorderInformationResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource क्लास। इमेज प्रिंट सेटिंग्स की बॉर्डर जानकारी वाला संसाधन"
type: docs
weight: 4110
url: /hi/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
{{< psd/tize >}}
## BorderInformationResource class

छवि प्रिंट सेटिंग्स की सीमा जानकारी वाला संसाधन।

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | संसाधन डेटा आकार को बाइट्स में प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम को प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट्स 0 से बना होता है)। |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर को प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | डेटा सहित संसाधन ब्लॉक आकार को बाइट्स में प्राप्त करता है। |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | बॉर्डर इकाइयों को प्राप्त करता है या सेट करता है। |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | बॉर्डर चौड़ाई को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों को मान्य करता है। |

## उदाहरण

निम्नलिखित उदाहरण BorderInformationResource संसाधन के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource को अपडेट करें
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### देखें भी

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


