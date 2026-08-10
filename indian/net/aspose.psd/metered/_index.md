---
title: "क्लास Metered"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Metered क्लास। मीटर की सेट करने के लिए मेथड्स प्रदान करता है"
type: docs
weight: 5610
url: /hi/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

मीटर की कुंजी सेट करने के लिए मेथड्स प्रदान करता है।

```csharp
public class Metered
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Metered](metered/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं। |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | उत्पाद का नाम प्राप्त करता है। |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | मीटर सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटर लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त होता है। हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफलता रहती है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट कर दिया जाएगा; ऐसी स्थिति से बचने के लिए, आपको नियमित रूप से लाइसेंस स्थिति जांचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें। |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | उपभोग क्रेडिट प्राप्त करता है |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | उपभोग फ़ाइल आकार प्राप्त करता है |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | जाँचें कि मीटर लाइसेंस प्राप्त है या नहीं |

## उदाहरण

इस उदाहरण में, मीटर सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


