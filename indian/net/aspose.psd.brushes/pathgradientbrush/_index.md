---
title: Class PathGradientBrush
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Brushes.PathGradientBrush कक्ष. एनकैप्सुलेट करत हैBrush ढल के सथ वस्तु इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 170
url: /hi/net/aspose.psd.brushes/pathgradientbrush/
---
## PathGradientBrush class

एनकैप्सुलेट करता है[`Brush`](../../aspose.psd/brush/) ढाल के साथ वस्तु। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | का एक नया उदाहरण प्रारंभ करता है`PathGradientBrush` वर्ग निर्दिष्ट पथ के साथ. |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | का एक नया उदाहरण प्रारंभ करता है`PathGradientBrush` वर्ग निर्दिष्ट अंक के साथ. |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | का एक नया उदाहरण प्रारंभ करता है`PathGradientBrush` वर्ग निर्दिष्ट अंक के साथ. |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | का एक नया उदाहरण प्रारंभ करता है`PathGradientBrush` वर्ग निर्दिष्ट अंक और रैप मोड के साथ . |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | का एक नया उदाहरण प्रारंभ करता है`PathGradientBrush` वर्ग निर्दिष्ट अंक और रैप मोड के साथ . |

## गुण

| नाम | विवरण |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | हो जाता है या सेट करता है[`Blend`](../../aspose.psd/blend/) जो उन स्थितियों और कारकों को निर्दिष्ट करता है जो ग्रेडिएंट के लिए एक कस्टम फ़ॉलऑफ़ को परिभाषित करते हैं। |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | पथ ढाल के केंद्र में रंग प्राप्त या सेट करता है। |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | पथ ढाल का केंद्र बिंदु प्राप्त या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | ग्रेडिएंट फ़ॉलऑफ़ के लिए फ़ोकस पॉइंट प्राप्त या सेट करता है। |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | उस ग्राफ़िक्स पथ को प्राप्त करता है जिस पर यह ब्रश बनाया गया था। |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि परिवर्तन किसी तरह से बदले गए थे या नहीं। उदाहरण के लिए ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना or ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने के किसी भी तरीके को कॉल करना। GDI+. के साथ पिछड़े संगतता के लिए गुण पेश किया गया है |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश अपारदर्शिता प्राप्त या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 के मान का अर्थ है कि ब्रश पूरी तरह से दिखाई दे रहा है, 1 के मान का अर्थ है कि ब्रश पूरी तरह से अपारदर्शी है। |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | उस पथ बिंदु को प्राप्त करता है जिस पर यह ब्रश बनाया गया था। |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | रंगों की एक सरणी प्राप्त या सेट करता है जो इस पथ में बिंदुओं के अनुरूप होता है`PathGradientBrush` भरता है. |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | बीच के रंग के साथ ग्रेडिएंट बनाता है और आस-पास के रंग के लिए एक रेखीय फ़ॉलऑफ़ बनाता है. |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | मध्य रंग के साथ एक ग्रेडिएंट बनाता है और प्रत्येक आसपास के रंग के लिए एक रेखीय फ़ॉलऑफ़ बनाता है। |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। एक रंग से दूसरे रंग में संक्रमण घंटी के आकार के वक्र पर आधारित होता है. |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। एक रंग से दूसरे रंग में संक्रमण घंटी के आकार के वक्र पर आधारित होता है. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। यह विधि ट्रांस्फ़ॉर्म के लिए अनुवाद को आगे बढ़ाती है. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। |

### टिप्पणियों

केंद्र का रंग डिफ़ॉल्ट रूप से सफेद होता है। उपयोगकर्ता बाद में किसी भी समय इस मान को बदल सकता है।

चारों ओर रंग सरणी डिफ़ॉल्ट रूप से सफेद रंग वाले एकल तत्व द्वारा प्रारंभ की जाती है। आसपास के रंगों को बाद में बदला जा सकता है, हालांकि आसपास के रंगों को सेट करते समय कम से कम एक तत्व की आवश्यकता होती है।

देखें[`Blend`](./blend/) इसके प्रारंभ के बारे में अधिक जानकारी के लिए।

### यह सभी देखें

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* नाम स्थान [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* सभा [Aspose.PSD](../../)


