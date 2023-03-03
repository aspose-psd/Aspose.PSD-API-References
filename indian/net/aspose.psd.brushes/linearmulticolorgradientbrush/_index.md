---
title: Class LinearMulticolorGradientBrush
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Brushes.LinearMulticolorGradientBrush कक्ष. एक क प्रतनधत्व करत हैBrush कई रंगं और उपयुक्त स्थतयं द्वर परभषत रैखक ढल के सथ इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 160
url: /hi/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

एक का प्रतिनिधित्व करता है[`Brush`](../../aspose.psd/brush/) कई रंगों और उपयुक्त स्थितियों द्वारा परिभाषित रैखिक ढाल के साथ। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`LinearMulticolorGradientBrush` डिफ़ॉल्ट मापदंडों के साथ वर्ग। शुरुआती रंग काला है, अंत का रंग सफेद है, कोण 45 डिग्री है और आयत आकार (1,1) के साथ (0,0) में स्थित है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | का एक नया उदाहरण प्रारंभ करता है`LinearMulticolorGradientBrush` वर्ग निर्दिष्ट अंक के साथ. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | का एक नया उदाहरण प्रारंभ करता है`LinearMulticolorGradientBrush` वर्ग निर्दिष्ट अंक के साथ. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | का एक नया उदाहरण प्रारंभ करता है`LinearMulticolorGradientBrush` वर्ग एक आयत और एक ओरिएंटेशन कोण पर आधारित है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | का एक नया उदाहरण प्रारंभ करता है`LinearMulticolorGradientBrush` वर्ग एक आयत और एक ओरिएंटेशन कोण पर आधारित है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | का एक नया उदाहरण प्रारंभ करता है`LinearMulticolorGradientBrush` वर्ग एक आयत और एक ओरिएंटेशन कोण पर आधारित है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | का एक नया उदाहरण प्रारंभ करता है`LinearMulticolorGradientBrush` वर्ग एक आयत और एक ओरिएंटेशन कोण पर आधारित है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | ग्रेडिएंट कोण प्राप्त या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि इसके लिए गामा सुधार सक्षम है या नहीं[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | हो जाता है या सेट करता है[`ColorBlend`](../../aspose.psd/colorblend/) जो एक बहुरंगा रैखिक ढाल को परिभाषित करता है। |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | यह इंगित करने वाला मान प्राप्त या सेट करता है[`Angle`](../lineargradientbrushbase/angle/) इसके साथ परिवर्तन के दौरान बदल दिया जाता है[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि परिवर्तन किसी तरह से बदले गए थे या नहीं। उदाहरण के लिए ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना or ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने के किसी भी तरीके को कॉल करना। GDI+. के साथ पिछड़े संगतता के लिए गुण पेश किया गया है |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश अपारदर्शिता प्राप्त या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 के मान का अर्थ है कि ब्रश पूरी तरह से दिखाई दे रहा है, 1 के मान का अर्थ है कि ब्रश पूरी तरह से अपारदर्शी है। |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | एक आयताकार क्षेत्र प्राप्त या सेट करता है जो ग्रेडिएंट के शुरुआती और अंत बिंदुओं को परिभाषित करता है। |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | कॉपी प्राप्त या सेट करता है[`Matrix`](../../aspose.psd/matrix/) जो इसके लिए एक स्थानीय ज्यामितीय परिवर्तन को परिभाषित करता है[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | हो जाता है या सेट करता है[`WrapMode`](../../aspose.psd/wrapmode/) एन्यूमरेशन जो इसके लिए रैप मोड को इंगित करता है[`TransformBrush`](../transformbrush/) . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | वर्तमान का एक नया गहरा क्लोन बनाता है[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | गुणा करता है[`Matrix`](../../aspose.psd/matrix/) जो इसके स्थानीय ज्यामितीय परिवर्तन का प्रतिनिधित्व करता है[`LinearGradientBrush`](../lineargradientbrush/) निर्दिष्ट द्वारा[`Matrix`](../../aspose.psd/matrix/) निर्दिष्ट तैयार करके[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | गुणा करता है[`Matrix`](../../aspose.psd/matrix/) जो इसके स्थानीय ज्यामितीय परिवर्तन का प्रतिनिधित्व करता है[`LinearGradientBrush`](../lineargradientbrush/) निर्दिष्ट द्वारा[`Matrix`](../../aspose.psd/matrix/) निर्दिष्ट क्रम में. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | रीसेट करता है[`Transform`](../transformbrush/transform/) पहचान के लिए संपत्ति। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | निर्दिष्ट राशि से स्थानीय ज्यामितीय परिवर्तन को घुमाता है। यह विधि रोटेशन को परिवर्तन से पहले जोड़ती है। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट राशि द्वारा स्थानीय ज्यामितीय परिवर्तन को घुमाता है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | निर्दिष्ट राशियों द्वारा स्थानीय ज्यामितीय परिवर्तन को मापता है। यह विधि स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म करने के लिए तैयार करती है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय परिवर्तन को स्केल करता है। |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। यह विधि ट्रांस्फ़ॉर्म के लिए अनुवाद को आगे बढ़ाती है. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। |

### यह सभी देखें

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* नाम स्थान [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* सभा [Aspose.PSD](../../)


