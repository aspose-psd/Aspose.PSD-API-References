---
title: Class PathGradientBrushBase
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Brushes.PathGradientBrushBase कक्ष. एक क प्रतनधत्व करत हैBrush आधर पथ ढल कर्यक्षमत के सथ.
type: docs
weight: 180
url: /hi/net/aspose.psd.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

एक का प्रतिनिधित्व करता है[`Brush`](../../aspose.psd/brush/) आधार पथ ढाल कार्यक्षमता के साथ.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## गुण

| नाम | विवरण |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | पथ ढाल का केंद्र बिंदु प्राप्त या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | ग्रेडिएंट फ़ॉलऑफ़ के लिए फ़ोकस पॉइंट प्राप्त या सेट करता है। |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | उस ग्राफ़िक्स पथ को प्राप्त करता है जिस पर यह ब्रश बनाया गया था। |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि परिवर्तन किसी तरह से बदले गए थे या नहीं। उदाहरण के लिए ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना or ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने के किसी भी तरीके को कॉल करना। GDI+. के साथ पिछड़े संगतता के लिए गुण पेश किया गया है |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश अपारदर्शिता प्राप्त या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 के मान का अर्थ है कि ब्रश पूरी तरह से दिखाई दे रहा है, 1 के मान का अर्थ है कि ब्रश पूरी तरह से अपारदर्शी है। |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | उस पथ बिंदु को प्राप्त करता है जिस पर यह ब्रश बनाया गया था। |
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

### टिप्पणियों

ध्यान दें कि बनाते समय`PathGradientBrushBase` कक्षा इसे कम से कम 2 बिंदुओं के साथ प्रारंभ किया जाना चाहिए। बनाया गया आंतरिक पथ हमेशा एक बंद आंकड़ा होगा, अंतिम बिंदु पहले बिंदु को जोड़ता है। इसी से वह आकृति भर जाती है`PathGradientBrushBase`. GDI+ कार्यान्वयन एक फेंकता हैOutOfMemoryException खाली सरणियों या समान निर्देशांक वाले बिंदुओं में गुजरते समय। द`PathGradientBrushBase` एक अपवाद फेंकता है जब बिंदु सरणी में 2 अंक से कम होते हैं,ArgumentException is इसके बजाय फेंका गयाOutOfMemoryException जब बिंदु सरणी अस्वीकार्य है। केंद्र बिंदु की गणना डिफ़ॉल्ट रूप से पारित बिंदुओं के द्रव्यमान के केंद्र के रूप में की जाती है। एक उपयोगकर्ता इस बिंदु को बाद में बदल सकता है। फोकस स्केल डिफ़ॉल्ट रूप से एक खाली बिंदु (0.0, 0.0) है।

### यह सभी देखें

* class [TransformBrush](../transformbrush/)
* नाम स्थान [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* सभा [Aspose.PSD](../../)


