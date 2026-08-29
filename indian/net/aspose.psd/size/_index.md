---
title: "Struct Size"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Size struct. आकार का प्रतिनिधित्व करता है"
type: docs
weight: 6050
url: /hi/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

आकार का प्रतिनिधित्व करता है।

```csharp
public struct Size
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Size](size/#constructor)(Point) | निर्दिष्ट [`Point`](../point/) से `Size` संरचना का नया उदाहरण प्रारंभ करता है। |
| [Size](size/#constructor_1)(int, int) | निर्दिष्ट आयामों से `Size` संरचना का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | `Size` संरचना का नया उदाहरण प्राप्त करता है जिसमें [`Width`](./width/) और [`Height`](./height/) मान शून्य पर सेट होते हैं। |
| [Height](../../aspose.psd/size/height/) { get; set; } | इस `Size` का लंबवत घटक प्राप्त करता है या सेट करता है। |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि इस `Size` की चौड़ाई और ऊँचाई 0 है या नहीं। |
| [Width](../../aspose.psd/size/width/) { get; set; } | इस `Size` का क्षैतिज घटक प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | एक `Size` संरचना की चौड़ाई और ऊँचाई को दूसरी `Size` संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | निर्दिष्ट [`SizeF`](../sizef/) संरचना को `Size` संरचना में परिवर्तित करता है, `Size` संरचना के मानों को अगले बड़े पूर्णांक मान तक गोल करके। |
| static [Round](../../aspose.psd/size/round/)(SizeF) | निर्दिष्ट [`SizeF`](../sizef/) संरचना को `Size` संरचना में परिवर्तित करता है, [`SizeF`](../sizef/) संरचना के मानों को निकटतम पूर्णांक मान तक गोल करके। |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | एक `Size` संरचना की चौड़ाई और ऊँचाई को दूसरी `Size` संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | निर्दिष्ट [`SizeF`](../sizef/) संरचना को `Size` संरचना में परिवर्तित करता है, [`SizeF`](../sizef/) संरचना के मानों को अगले छोटे पूर्णांक मान तक काटकर। |
| override [Equals](../../aspose.psd/size/equals/)(object) | जाँचता है कि क्या निर्दिष्ट वस्तु इस `Size` के समान आयामों वाला `Size` है। |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | इस `Size` संरचना के लिए एक हैश कोड लौटाता है। |
| override [ToString](../../aspose.psd/size/tostring/)() | एक मानव‑पठनीय स्ट्रिंग बनाता है जो इस `Size` का प्रतिनिधित्व करता है। |
| [operator +](../../aspose.psd/size/op_addition/) | एक `Size` संरचना की चौड़ाई और ऊँचाई को दूसरी `Size` संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [operator ==](../../aspose.psd/size/op_equality/) | जाँचता है कि दो `Size` संरचनाएँ समान हैं या नहीं। |
| [explicit operator](../../aspose.psd/size/op_explicit/) | निर्दिष्ट `Size` को [`Point`](../point/) में परिवर्तित करता है। |
| [implicit operator](../../aspose.psd/size/op_implicit/) | निर्दिष्ट `Size` को [`SizeF`](../sizef/) में परिवर्तित करता है। |
| [operator !=](../../aspose.psd/size/op_inequality/) | जाँचता है कि दो `Size` संरचनाएँ अलग हैं या नहीं। |
| [operator -](../../aspose.psd/size/op_subtraction/) | एक `Size` संरचना की चौड़ाई और ऊँचाई को दूसरी `Size` संरचना की चौड़ाई और ऊँचाई से घटाता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


