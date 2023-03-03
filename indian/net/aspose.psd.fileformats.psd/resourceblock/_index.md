---
title: Class ResourceBlock
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.ResourceBlock कक्ष. संसधन ब्लक
type: docs
weight: 3610
url: /hi/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

संसाधन ब्लॉक।

```csharp
public abstract class ResourceBlock
```

## गुण

| नाम | विवरण |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | बाइट्स में संसाधन डेटा आकार प्राप्त करता है। |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त या सेट करता है। |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | न्यूनतम आवश्यक PSD संस्करण प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | संसाधन नाम प्राप्त या सेट करता है। पास्कल स्ट्रिंग, आकार को समान बनाने के लिए गद्देदार (शून्य नाम में 0 के दो बाइट होते हैं). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | अपने डेटा सहित बाइट्स में संसाधन ब्लॉक आकार प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | संसाधन ब्लॉक को निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | संसाधन मानों की पुष्टि करता है. |

## खेत

| नाम | विवरण |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady. का संसाधन हस्ताक्षर |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | नियमित फोटोशॉप संसाधन हस्ताक्षर। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | संसाधन ब्लॉक स्थिति का प्रतिनिधित्व करता है। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* सभा [Aspose.PSD](../../)


