---
title: Class BackgroundColorResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource कक्ष. छव प्रंट सेटंग्स क सम जनकर वल संसधन
type: docs
weight: 3640
url: /hi/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
## BackgroundColorResource class

छवि प्रिंट सेटिंग्स की सीमा जानकारी वाला संसाधन।

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | पृष्ठभूमि का रंग प्राप्त या सेट करता है। |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | बाइट्स में संसाधन डेटा आकार प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त या सेट करता है। |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम प्राप्त या सेट करता है। पास्कल स्ट्रिंग, आकार को समान बनाने के लिए गद्देदार (शून्य नाम में 0 के दो बाइट होते हैं). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | अपने डेटा सहित बाइट्स में संसाधन ब्लॉक आकार प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | संसाधन ब्लॉक को निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों की पुष्टि करता है. |

### उदाहरण

निम्न उदाहरण पृष्ठभूमिरंग संसाधन संसाधन के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // अद्यतन पृष्ठभूमि रंग संसाधन
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### यह सभी देखें

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* सभा [Aspose.PSD](../../)


