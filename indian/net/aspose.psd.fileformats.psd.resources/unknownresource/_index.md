---
title: "क्लास UnknownResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Resources.UnknownResource क्लास। अज्ञात संसाधन। जब कोई रिसोर्स ब्लॉक पहचाना नहीं जाता है, तब यह रिसोर्स ब्लॉक बनाया जाता है।"
type: docs
weight: 4410
url: /hi/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
{{< psd/tize >}}
## UnknownResource class

अज्ञात संसाधन। जब कोई संसाधन ब्लॉक पहचाना नहीं जाता है तो यह संसाधन ब्लॉक बनाया जाता है।

```csharp
public sealed class UnknownResource : ResourceBlock
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | संसाधन डेटा प्राप्त करता है। |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | संसाधन डेटा आकार को बाइट्स में प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम को प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट्स 0 से बना होता है)। |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर को प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | डेटा सहित संसाधन ब्लॉक आकार को बाइट्स में प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों को मान्य करता है। |

### देखें भी

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


