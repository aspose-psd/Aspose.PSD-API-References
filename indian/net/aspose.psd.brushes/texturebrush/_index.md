---
title: "क्लास TextureBrush"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Brushes.TextureBrush क्लास। TextureBrush क्लास की प्रत्येक प्रॉपर्टी एक Brush ऑब्जेक्ट है जो किसी आकार के भीतर को भरने के लिए छवि का उपयोग करती है। इस क्लास को विरासत में नहीं लिया जा सकता।"
type: docs
weight: 210
url: /hi/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

`TextureBrush` क्लास की प्रत्येक प्रॉपर्टी एक [`Brush`](../../aspose.psd/brush/) ऑब्जेक्ट है जो किसी आकार के भीतर को भरने के लिए छवि का उपयोग करती है। इस क्लास को विरासत में नहीं लिया जा सकता।

```csharp
public sealed class TextureBrush : TransformBrush
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | निर्दिष्ट छवि का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | निर्दिष्ट छवि और रैप मोड का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | निर्दिष्ट छवि, बाउंडिंग आयत, और छवि विशेषताओं का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | निर्दिष्ट छवि, बाउंडिंग आयत, और छवि विशेषताओं का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | निर्दिष्ट छवि, रैप मोड, और बाउंडिंग आयत का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | निर्दिष्ट छवि, रैप मोड, और बाउंडिंग आयत का उपयोग करने वाली `TextureBrush` क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | `TextureBrush` ऑब्जेक्ट से संबंधित [`Image`](../../aspose.psd/image/) ऑब्जेक्ट प्राप्त करता है। |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | `TextureBrush` से संबंधित [`ImageAttributes`](./imageattributes/) प्राप्त करता है। |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | `TextureBrush` से संबंधित [`Rectangle`](../../aspose.psd/rectangle/) प्राप्त करता है। |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ट्रांसफ़ॉर्मेशन किसी न किसी तरह बदले गए थे या नहीं। उदाहरण के लिए, ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना या ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने वाले किसी भी मेथड को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पीछे की संगतता के लिए पेश की गई है। |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश की अपारदर्शिता प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह से दिखाई देता है, 1 का मान मतलब ब्रश पूरी तरह से अपारदर्शी है। |
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

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


