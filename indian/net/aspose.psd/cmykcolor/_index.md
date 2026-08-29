---
title: "संरचना CmykColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.CmykColor संरचना। पिक्सेल का CMYK रंग"
type: docs
weight: 270
url: /hi/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

पिक्सेल का CMYK रंग।

```csharp
public struct CmykColor
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | खाली प्राप्त करता है। |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | इस [`Color`](../color/) संरचना का सियान घटक मान प्राप्त करता है। |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | इस [`Color`](../color/) संरचना के अनइनिशियलाइज़्ड होने को दर्शाने वाला मान प्राप्त करता है। |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | इस [`Color`](../color/) संरचना के काले घटक का मान प्राप्त करता है। |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | इस [`Color`](../color/) संरचना के मैजेंटा घटक का मान प्राप्त करता है। |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | इस [`Color`](../color/) संरचना के पीले घटक का मान प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | 32-बिट सियान, मैजेंटा, येलो और ब्लैक मानों से एक `CmykColor` संरचना बनाता है। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`FromComponents`](../cmykcolorhelper/fromcomponents/) का उपयोग करें। |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | 32-बिट ARGB से CMYKColor में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToCmyk`](../cmykcolorhelper/tocmyk/) का उपयोग करें। |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | हैश कोड प्राप्त करता है। |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | मान प्राप्त करता है। |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से 32-बिट ARGB Color में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToArgb32`](../cmykcolorhelper/toargb32/) का उपयोग करें। |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | 32-बिट ARGB रंग से CMYKColor में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToCmyk`](../cmykcolorhelper/tocmyk/) का उपयोग करें। |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | CMYKColor से Color में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToArgb`](../cmykcolorhelper/toargb/) का उपयोग करें। |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToArgb`](../cmykcolorhelper/toargb/) का उपयोग करें। |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) का उपयोग करें। |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) का उपयोग करें। |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) का उपयोग करें। |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड पुराना हो गया है। कृपया अधिक प्रभावी [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) का उपयोग करें। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


