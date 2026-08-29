---
title: "क्लास LinearMulticolorGradientBrush"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Brushes.LinearMulticolorGradientBrush क्लास। कई रंगों और उपयुक्त स्थितियों द्वारा परिभाषित रैखिक ग्रेडिएंट के साथ एक ब्रश का प्रतिनिधित्व करता है। यह क्लास विरासत में नहीं ली जा सकती।"
type: docs
weight: 160
url: /hi/net/aspose.psd.brushes/linearmulticolorgradientbrush/
---
{{< psd/tize >}}
## LinearMulticolorGradientBrush class

एक [`Brush`](../../aspose.psd/brush/) का प्रतिनिधित्व करता है जिसमें कई रंगों और उपयुक्त स्थितियों द्वारा परिभाषित रैखिक ग्रेडिएंट है। यह क्लास विरासत में नहीं ली जा सकती।

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor)() | `LinearMulticolorGradientBrush` क्लास का नया इंस्टेंस डिफ़ॉल्ट पैरामीटरों के साथ इनिशियलाइज़ करता है। प्रारंभिक रंग काला है, अंतिम रंग सफ़ेद है, कोण 45 डिग्री है और आयत (0,0) में स्थित है जिसका आकार (1,1) है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_1)(Point, Point) | `LinearMulticolorGradientBrush` क्लास का नया इंस्टेंस निर्दिष्ट बिंदुओं के साथ इनिशियलाइज़ करता है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_2)(PointF, PointF) | `LinearMulticolorGradientBrush` क्लास का नया इंस्टेंस निर्दिष्ट बिंदुओं के साथ इनिशियलाइज़ करता है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_3)(Rectangle, float) | `LinearMulticolorGradientBrush` क्लास का नया इंस्टेंस आयत और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_5)(RectangleF, float) | `LinearMulticolorGradientBrush` क्लास का नया इंस्टेंस आयत और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_4)(Rectangle, float, bool) | `LinearMulticolorGradientBrush` क्लास का नया इंस्टेंस आयत और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush/#constructor_6)(RectangleF, float, bool) | `LinearMulticolorGradientBrush` क्लास का नया इंस्टेंस आयत और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | ग्रेडिएंट कोण प्राप्त करता है या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि इस [`LinearGradientBrushBase`](../lineargradientbrushbase/) के लिए गामा सुधार सक्षम है या नहीं। |
| [InterpolationColors](../../aspose.psd.brushes/linearmulticolorgradientbrush/interpolationcolors/) { get; set; } | एक [`ColorBlend`](../../aspose.psd/colorblend/) प्राप्त करता है या सेट करता है जो बहु‑रंग रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि इस [`LinearGradientBrushBase`](../lineargradientbrushbase/) के साथ ट्रांसफ़ॉर्मेशन के दौरान [`Angle`](../lineargradientbrushbase/angle/) बदला गया है या नहीं। |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ट्रांसफ़ॉर्मेशन किसी न किसी तरह बदले गए थे या नहीं। उदाहरण के लिए, ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना या ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने वाले किसी भी मेथड को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पीछे की संगतता के लिए पेश की गई है। |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश की अपारदर्शिता प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह से दिखाई देता है, 1 का मान मतलब ब्रश पूरी तरह से अपारदर्शी है। |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करने वाले आयताकार क्षेत्र को प्राप्त करता है या सेट करता है। |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट आयामों से अनुवादित करता है। यह मेथड ट्रांसलेशन को रूपांतरण के पहले जोड़ता है। |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट आयामों से अनुवादित करता है। |

### देखें भी

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


