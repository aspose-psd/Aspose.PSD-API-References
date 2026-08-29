---
title: "License.SetLicense"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "License मेथड। घटक को लाइसेंस देता है"
type: docs
weight: 20
url: /hi/net/aspose.psd/license/setlicense/
---
{{< psd/tize >}}
## SetLicense(string) {#setlicense_1}

घटक को लाइसेंस करता है।

```csharp
public void SetLicense(string licenseName)
```

## टिप्पणियाँ

निम्नलिखित स्थानों में लाइसेंस खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. वह फ़ोल्डर जिसमें Aspose घटक असेंबली शामिल है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग असेंबली शामिल है।

4. वह फ़ोल्डर जिसमें एंट्री (स्टार्टअप) असेंबली शामिल है।

5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

## उदाहरण

इस उदाहरण में, घटक वाली फ़ोल्डर, कॉलिंग असेंबली वाली फ़ोल्डर, एंट्री असेंबली वाली फ़ोल्डर, और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्सेज़ में MyLicense.lic नाम की लाइसेंस फ़ाइल खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

पूरा या छोटा फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें।

### देखें भी

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस करता है।

```csharp
public void SetLicense(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

## टिप्पणियाँ

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।

## उदाहरण

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### देखें भी

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


