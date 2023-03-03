---
title: Class LinearGradientBrush
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Brushes.LinearGradientBrush कक्ष. एनकैप्सुलेट करत हैBrush एक रेखय ढल के सथ इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 140
url: /hi/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

एनकैप्सुलेट करता है[`Brush`](../../aspose.psd/brush/) एक रेखीय ढाल के साथ। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`LinearGradientBrush` डिफ़ॉल्ट मापदंडों के साथ वर्ग। शुरुआती रंग काला है, अंत का रंग सफेद है, कोण 45 डिग्री है और आयत आकार (1,1) के साथ (0,0) में स्थित है। |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | का एक नया उदाहरण प्रारंभ करता है`LinearGradientBrush` वर्ग निर्दिष्ट बिंदुओं और रंगों के साथ। |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | का एक नया उदाहरण प्रारंभ करता है`LinearGradientBrush` वर्ग निर्दिष्ट बिंदुओं और रंगों के साथ। |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | का एक नया उदाहरण प्रारंभ करता है`LinearGradientBrush` वर्ग एक आयत पर आधारित है, शुरू और समाप्त रंग, और एक ओरिएंटेशन कोण. |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | का एक नया उदाहरण प्रारंभ करता है`LinearGradientBrush` वर्ग एक आयत पर आधारित है, शुरू और समाप्त रंग, और एक ओरिएंटेशन कोण. |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | का एक नया उदाहरण प्रारंभ करता है`LinearGradientBrush` वर्ग एक आयत पर आधारित है, शुरू और समाप्त रंग, और एक ओरिएंटेशन कोण. |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | का एक नया उदाहरण प्रारंभ करता है`LinearGradientBrush` वर्ग एक आयत पर आधारित है, शुरू और समाप्त रंग, और एक ओरिएंटेशन कोण. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | ग्रेडिएंट कोण प्राप्त या सेट करता है। |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | हो जाता है या सेट करता है[`Blend`](../../aspose.psd/blend/) जो उन स्थितियों और कारकों को निर्दिष्ट करता है जो ग्रेडिएंट के लिए एक कस्टम फ़ॉलऑफ़ को परिभाषित करते हैं। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | अंतिम ग्रेडिएंट रंग प्राप्त या सेट करता है। |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि इसके लिए गामा सुधार सक्षम है या नहीं[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | यह इंगित करने वाला मान प्राप्त या सेट करता है[`Angle`](../lineargradientbrushbase/angle/) इसके साथ परिवर्तन के दौरान बदल दिया जाता है[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि परिवर्तन किसी तरह से बदले गए थे या नहीं। उदाहरण के लिए ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना or ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने के किसी भी तरीके को कॉल करना। GDI+. के साथ पिछड़े संगतता के लिए गुण पेश किया गया है |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश अपारदर्शिता प्राप्त या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 के मान का अर्थ है कि ब्रश पूरी तरह से दिखाई दे रहा है, 1 के मान का अर्थ है कि ब्रश पूरी तरह से अपारदर्शी है। |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | एक आयताकार क्षेत्र प्राप्त या सेट करता है जो ग्रेडिएंट के शुरुआती और अंत बिंदुओं को परिभाषित करता है। |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | प्रारंभिक ढाल रंग प्राप्त या सेट करता है। |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | कॉपी प्राप्त या सेट करता है[`Matrix`](../../aspose.psd/matrix/) जो इसके लिए एक स्थानीय ज्यामितीय परिवर्तन को परिभाषित करता है[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | हो जाता है या सेट करता है[`WrapMode`](../../aspose.psd/wrapmode/) एन्यूमरेशन जो इसके लिए रैप मोड को इंगित करता है[`TransformBrush`](../transformbrush/) . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | वर्तमान का एक नया गहरा क्लोन बनाता है[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | गुणा करता है[`Matrix`](../../aspose.psd/matrix/) जो इसके स्थानीय ज्यामितीय परिवर्तन का प्रतिनिधित्व करता है`LinearGradientBrush` निर्दिष्ट द्वारा[`Matrix`](../../aspose.psd/matrix/) निर्दिष्ट तैयार करके[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | गुणा करता है[`Matrix`](../../aspose.psd/matrix/) जो इसके स्थानीय ज्यामितीय परिवर्तन का प्रतिनिधित्व करता है`LinearGradientBrush` निर्दिष्ट द्वारा[`Matrix`](../../aspose.psd/matrix/) निर्दिष्ट क्रम में. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | रीसेट करता है[`Transform`](../transformbrush/transform/) पहचान के लिए संपत्ति। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | निर्दिष्ट राशि से स्थानीय ज्यामितीय परिवर्तन को घुमाता है। यह विधि रोटेशन को परिवर्तन से पहले जोड़ती है। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट राशि द्वारा स्थानीय ज्यामितीय परिवर्तन को घुमाता है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | निर्दिष्ट राशियों द्वारा स्थानीय ज्यामितीय परिवर्तन को मापता है। यह विधि स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म करने के लिए तैयार करती है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय परिवर्तन को स्केल करता है। |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | बीच के रंग के साथ एक रेखीय ग्रेडिएंट बनाता है और दोनों सिरों पर एक ही रंग के लिए एक रैखिक फॉलऑफ़ बनाता है। |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | बीच के रंग के साथ एक रेखीय ग्रेडिएंट बनाता है और दोनों सिरों पर एक ही रंग के लिए एक रैखिक फॉलऑफ़ बनाता है। |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | घंटी के आकार के वक्र के आधार पर ग्रेडिएंट फ़ॉलऑफ़ बनाता है। |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | घंटी के आकार के वक्र के आधार पर ग्रेडिएंट फ़ॉलऑफ़ बनाता है। |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। यह विधि ट्रांस्फ़ॉर्म के लिए अनुवाद को आगे बढ़ाती है. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। |

### यह सभी देखें

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* नाम स्थान [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* सभा [Aspose.PSD](../../)


