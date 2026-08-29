---
title: "क्लास TransformBrush"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Brushes.TransformBrush क्लास। ट्रांसफ़ॉर्म क्षमताओं वाला एक Brush।"
type: docs
weight: 220
url: /hi/net/aspose.psd.brushes/transformbrush/
---
{{< psd/tize >}}
## TransformBrush class

ट्रांसफ़ॉर्म क्षमताओं वाला एक [`Brush`](../../aspose.psd/brush/)।

```csharp
public abstract class TransformBrush : Brush
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ट्रांसफ़ॉर्मेशन किसी न किसी तरह बदले गए थे या नहीं। उदाहरण के लिए, ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना या ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने वाले किसी भी मेथड को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पीछे की संगतता के लिए पेश की गई है। |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश की अपारदर्शिता प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह से दिखाई देता है, 1 का मान मतलब ब्रश पूरी तरह से अपारदर्शी है। |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | `TransformBrush` के लिए स्थानीय ज्यामितीय ट्रांसफ़ॉर्म परिभाषित करने वाला एक कॉपी [`Matrix`](../../aspose.psd/matrix/) प्राप्त करता है या सेट करता है। |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | `TransformBrush` के लिए रैप मोड दर्शाने वाला एक [`WrapMode`](../../aspose.psd/wrapmode/) एन्यूमरेशन प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | वर्तमान [`Brush`](../../aspose.psd/brush/) की एक नई डीप क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | इस [`LinearGradientBrush`](../lineargradientbrush/) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [`Matrix`](../../aspose.psd/matrix/) को निर्दिष्ट किए गए [`Matrix`](../../aspose.psd/matrix/) से गुणा करता है, निर्दिष्ट किए गए [`Matrix`](../../aspose.psd/matrix/) को पहले जोड़कर। |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | इस [`LinearGradientBrush`](../lineargradientbrush/) के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [`Matrix`](../../aspose.psd/matrix/) को निर्दिष्ट किए गए क्रम में निर्दिष्ट किए गए [`Matrix`](../../aspose.psd/matrix/) से गुणा करता है। |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | [`Transform`](./transform/) प्रॉपर्टी को पहचान पर रीसेट करता है। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घूर्णन को रूपांतरण के पहले जोड़ता है। |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट मात्रा से घुमाता है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को रूपांतरण के पहले जोड़ता है। |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट मात्राओं से स्केल करता है। |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट आयामों से अनुवादित करता है। यह मेथड ट्रांसलेशन को रूपांतरण के पहले जोड़ता है। |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट आयामों से अनुवादित करता है। |

### देखें भी

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


