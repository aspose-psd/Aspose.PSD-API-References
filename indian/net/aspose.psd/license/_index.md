---
title: "क्लास License"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.License क्लास। घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।"
type: docs
weight: 5540
url: /hi/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

घटक को लाइसेंस करने के लिए मेथड्स प्रदान करता है।

```csharp
public class License
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [License](license/)() | इस क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | घटक को लाइसेंस करता है। |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | घटक को लाइसेंस करता है। |

## उदाहरण

इस उदाहरण में, घटक वाली फ़ोल्डर, कॉलिंग असेंबली वाली फ़ोल्डर, एंट्री असेंबली वाली फ़ोल्डर, और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्सेज़ में MyLicense.lic नाम की लाइसेंस फ़ाइल खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


