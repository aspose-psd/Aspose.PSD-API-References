---
title: "क्लास PathGradientBrush"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Brushes.PathGradientBrush क्लास। ग्रेडिएंट वाले ब्रश ऑब्जेक्ट को संलग्न करता है। यह क्लास विरासत में नहीं ली जा सकती।"
type: docs
weight: 170
url: /hi/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

ग्रेडिएंट के साथ एक [`Brush`](../../aspose.psd/brush/) ऑब्जेक्ट को संलग्न करता है। यह क्लास विरासत में नहीं ली जा सकती।

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | निर्दिष्ट पथ के साथ `PathGradientBrush` क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | निर्दिष्ट बिंदुओं के साथ `PathGradientBrush` क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | निर्दिष्ट बिंदुओं के साथ `PathGradientBrush` क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | निर्दिष्ट बिंदुओं और रैप मोड के साथ `PathGradientBrush` क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | निर्दिष्ट बिंदुओं और रैप मोड के साथ `PathGradientBrush` क्लास का नया इंस्टेंस प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | एक [`Blend`](../../aspose.psd/blend/) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फ़ॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है। |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | पथ ग्रेडिएंट के केंद्र पर रंग प्राप्त करता है या सेट करता है। |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | पाथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | ग्रेडिएंट फॉलऑफ़ के लिए फोकस बिंदु को प्राप्त करता है या सेट करता है। |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | इस ब्रश द्वारा निर्मित ग्राफिक्स पाथ को प्राप्त करता है। |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | एक [`ColorBlend`](../../aspose.psd/colorblend/) प्राप्त करता है या सेट करता है जो बहु‑रंग रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ट्रांसफ़ॉर्मेशन किसी न किसी तरह बदले गए थे या नहीं। उदाहरण के लिए, ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना या ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने वाले किसी भी मेथड को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पीछे की संगतता के लिए पेश की गई है। |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश की अपारदर्शिता प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह से दिखाई देता है, 1 का मान मतलब ब्रश पूरी तरह से अपारदर्शी है। |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | इस ब्रश द्वारा निर्मित पाथ पॉइंट्स को प्राप्त करता है। |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | इस `PathGradientBrush` द्वारा भरे गए पथ के बिंदुओं से मेल खाने वाले रंगों की एक सरणी प्राप्त करता है या सेट करता है। |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | इस [`TransformBrush`](../transformbrush/) के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाली एक प्रति [`Matrix`](../../aspose.psd/matrix/) को प्राप्त करता है या सेट करता है। |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | इस [`TransformBrush`](../transformbrush/) के लिए रैप मोड को दर्शाने वाली एक [`WrapMode`](../../aspose.psd/wrapmode/) एन्यूमरेशन को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | वर्तमान [`Brush`](../../aspose.psd/brush/) की एक नई डीप क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | इस [`LinearGradientBrush`](../lineargradientbrush/) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [`Matrix`](../../aspose.psd/matrix/) को निर्दिष्ट किए गए [`Matrix`](../../aspose.psd/matrix/) से गुणा करता है, निर्दिष्ट किए गए [`Matrix`](../../aspose.psd/matrix/) को पहले जोड़कर। |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | इस [`LinearGradientBrush`](../lineargradientbrush/) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [`Matrix`](../../aspose.psd/matrix/) को निर्दिष्ट किए गए क्रम में निर्दिष्ट किए गए [`Matrix`](../../aspose.psd/matrix/) से गुणा करता है। |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | [`Transform`](../transformbrush/transform/) प्रॉपर्टी को पहचान पर रीसेट करता है। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घूर्णन को रूपांतरण के पहले जोड़ता है। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट मात्रा से घुमाता है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को रूपांतरण के पहले जोड़ता है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट मात्राओं से स्केल करता है। |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | एक ग्रेडिएंट बनाता है जिसमें केंद्र रंग है और एक आसपास के रंग तक रैखिक गिरावट होती है। |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | एक ग्रेडिएंट बनाता है जिसमें केंद्र रंग है और प्रत्येक आसपास के रंग तक रैखिक गिरावट होती है। |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। एक रंग से दूसरे रंग में परिवर्तन घंटी के आकार की वक्र पर आधारित होता है। |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। एक रंग से दूसरे रंग में परिवर्तन घंटी के आकार की वक्र पर आधारित होता है। |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट आयामों से अनुवादित करता है। यह मेथड ट्रांसलेशन को रूपांतरण के पहले जोड़ता है। |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट आयामों से अनुवादित करता है। |

## टिप्पणियाँ

केंद्र रंग डिफ़ॉल्ट रूप से सफ़ेद है। उपयोगकर्ता बाद में कभी भी इस मान को बदल सकता है।

आसपास के रंगों की सरणी डिफ़ॉल्ट रूप से सफ़ेद रंग वाले एकल तत्व से प्रारंभ की जाती है। आसपास के रंगों को बाद में बदला जा सकता है, लेकिन सेटअप करते समय कम से कम एक तत्व आवश्यक है।

इसके प्रारंभिकरण के बारे में अधिक विवरण के लिए [`Blend`](./blend/) देखें।

### देखें भी

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


