---
title: Class TextureBrush
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Brushes.TextureBrush कक्ष. क प्रत्येक संपत्तTextureBrush वर्ग एक हैBrush वस्तु ज कस आकृत के आंतरक भग क भरने के लए एक छव क उपयग करत है इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 210
url: /hi/net/aspose.psd.brushes/texturebrush/
---
## TextureBrush class

की प्रत्येक संपत्ति`TextureBrush` वर्ग एक है[`Brush`](../../aspose.psd/brush/) वस्तु जो किसी आकृति के आंतरिक भाग को भरने के लिए एक छवि का उपयोग करती है। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class TextureBrush : TransformBrush
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush` वर्ग जो निर्दिष्ट छवि का उपयोग करता है। |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush` वर्ग जो निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करता है। |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush` वर्ग जो निर्दिष्ट छवि और बाउंडिंग आयत का उपयोग करता है। |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush` वर्ग जो निर्दिष्ट छवि और रैप मोड का उपयोग करता है। |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush` वर्ग जो निर्दिष्ट छवि, बाउंडिंग आयत और छवि विशेषताओं का उपयोग करता है। |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush` वर्ग जो निर्दिष्ट छवि, बाउंडिंग आयत और छवि विशेषताओं का उपयोग करता है। |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush`वर्ग जो निर्दिष्ट छवि, रैप मोड और बाउंडिंग आयत का उपयोग करता है। |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | का एक नया उदाहरण प्रारंभ करता है`TextureBrush`वर्ग जो निर्दिष्ट छवि, रैप मोड और बाउंडिंग आयत का उपयोग करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | हो जाता है[`Image`](../../aspose.psd/image/) इससे जुड़ी वस्तु`TextureBrush` वस्तु. |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | हो जाता है[`ImageAttributes`](./imageattributes/) इससे जुड़ा हुआ है`TextureBrush` . |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | हो जाता है[`Rectangle`](../../aspose.psd/rectangle/) इससे जुड़ा हुआ है`TextureBrush` . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि परिवर्तन किसी तरह से बदले गए थे या नहीं। उदाहरण के लिए ट्रांसफ़ॉर्मेशन मैट्रिक्स सेट करना or ट्रांसफ़ॉर्मेशन मैट्रिक्स को बदलने के किसी भी तरीके को कॉल करना। GDI+. के साथ पिछड़े संगतता के लिए गुण पेश किया गया है |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश अपारदर्शिता प्राप्त या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 के मान का अर्थ है कि ब्रश पूरी तरह से दिखाई दे रहा है, 1 के मान का अर्थ है कि ब्रश पूरी तरह से अपारदर्शी है। |
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

* class [TransformBrush](../transformbrush/)
* नाम स्थान [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* सभा [Aspose.PSD](../../)


