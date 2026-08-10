---
title: "क्लास ResourceBlock"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.ResourceBlock क्लास। रिसोर्स ब्लॉक"
type: docs
weight: 4070
url: /hi/net/aspose.psd.fileformats.psd/resourceblock/
---
{{< psd/tize >}}
## ResourceBlock class

रिसोर्स ब्लॉक।

```csharp
public abstract class ResourceBlock
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | संसाधन डेटा आकार को बाइट्स में प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम को प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट्स 0 से बना होता है)। |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर को प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | डेटा सहित संसाधन ब्लॉक आकार को बाइट्स में प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों को मान्य करता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady की रिसोर्स सिग्नेचर। |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | सामान्य Photoshop रिसोर्स सिग्नेचर। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| enum [ResourceBlockState](../../aspose.psd.fileformats.psd/resourceblock.resourceblockstate) | रिसोर्स ब्लॉक स्थिति को दर्शाता है। |

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


