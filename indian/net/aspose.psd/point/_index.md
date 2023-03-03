---
title: Struct Point
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Point struct. पूर्णंक x और yनर्देशंकं क एक आदेशत जड़ क प्रतनधत्व करत है ज द्वआयम वमन में एक बंदु क परभषत करत है
type: docs
weight: 5260
url: /hi/net/aspose.psd/point/
---
## Point structure

पूर्णांक x- और y-निर्देशांकों की एक आदेशित जोड़ी का प्रतिनिधित्व करता है जो द्वि-आयामी विमान में एक बिंदु को परिभाषित करता है।

```csharp
public struct Point
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Point](point/#constructor_1)(int) | का एक नया उदाहरण प्रारंभ करता है`Point` एक पूर्णांक मान द्वारा निर्दिष्ट निर्देशांक का उपयोग कर संरचना। |
| [Point](point/#constructor)(Size) | का एक नया उदाहरण प्रारंभ करता है`Point` से संरचना[`Size`](../size/)संरचना. |
| [Point](point/#constructor_2)(int, int) | का एक नया उदाहरण प्रारंभ करता है`Point` निर्दिष्ट निर्देशांक के साथ संरचना. |

## गुण

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | का एक नया उदाहरण प्राप्त करता है`Point` संरचना जिसमें है[`X`](./x/) और[`Y`](./y/) मान शून्य पर सेट. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह`Point` खाली है. |
| [X](../../aspose.psd/point/x/) { get; set; } | इसका x-निर्देशांक प्राप्त या सेट करता है`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | इसका y-निर्देशांक प्राप्त या सेट करता है`Point` . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | निर्दिष्ट जोड़ता है[`Size`](../size/) निर्दिष्ट करने के लिए`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | निर्दिष्ट को परिवर्तित करता है[`PointF`](../pointf/) एक के लिए`Point` के मूल्यों को गोल करके[`PointF`](../pointf/) अगले उच्च पूर्णांक मानों के लिए। |
| static [Round](../../aspose.psd/point/round/)(PointF) | निर्दिष्ट को परिवर्तित करता है[`PointF`](../pointf/) एक के लिए`Point` गोल करके वस्तु`Point` निकटतम पूर्णांक के मान. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | निर्दिष्ट घटाव का परिणाम लौटाता है[`Size`](../size/) निर्दिष्ट से`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | निर्दिष्ट को परिवर्तित करता है[`PointF`](../pointf/) एक के लिए`Point` के मूल्यों को छोटा करके`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | निर्दिष्ट करता है कि क्या यह`Point` निर्दिष्ट के समान निर्देशांक शामिल हैंObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | इसके लिए हैश कोड लौटाता है`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | इसका अनुवाद करता है`Point` निर्दिष्ट द्वारा`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | इसका अनुवाद करता है`Point`निर्दिष्ट राशि से. |
| override [ToString](../../aspose.psd/point/tostring/)() | इसे परिवर्तित करता है`Point` एक मानव-पठनीय स्ट्रिंग के लिए. |
| [operator +](../../aspose.psd/point/op_addition/) | अनुवाद करता है`Point` एक दिए गए द्वारा[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | दो की तुलना करता है`Point` वस्तुओं। परिणाम निर्दिष्ट करता है कि क्या के मान[`X`](./x/) और[`Y`](./y/) दो के गुण`Point` वस्तुएं बराबर हैं। |
| [explicit operator](../../aspose.psd/point/op_explicit/) | निर्दिष्ट को परिवर्तित करता है`Point` ए के लिए संरचना[`Size`](../size/)संरचना. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | निर्दिष्ट को परिवर्तित करता है`Point` संरचना को[`PointF`](../pointf/)संरचना. |
| [operator !=](../../aspose.psd/point/op_inequality/) | दो की तुलना करता है`Point` वस्तुओं। परिणाम निर्दिष्ट करता है कि क्या के मान[`X`](./x/) या[`Y`](./y/) दो के गुण`Point` वस्तुएं असमान हैं। |
| [operator -](../../aspose.psd/point/op_subtraction/) | अनुवाद करता है`Point` किसी दिए गए के नकारात्मक द्वारा[`Size`](../size/) . |

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


