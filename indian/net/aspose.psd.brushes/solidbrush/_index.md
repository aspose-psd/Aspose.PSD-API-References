---
title: Class SolidBrush
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Brushes.SolidBrush कक्ष. ठस ब्रश वशष्ट रंग के सथ लगतर चत्र बनने के लए है इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 200
url: /hi/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

ठोस ब्रश विशिष्ट रंग के साथ लगातार चित्र बनाने के लिए है। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class SolidBrush : Brush
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`SolidBrush` वर्ग. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | का एक नया उदाहरण प्रारंभ करता है`SolidBrush` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | ब्रश का रंग प्राप्त या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश अपारदर्शिता प्राप्त या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 के मान का अर्थ है कि ब्रश पूरी तरह से दिखाई दे रहा है, 1 के मान का अर्थ है कि ब्रश पूरी तरह से अपारदर्शी है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | वर्तमान का एक नया गहरा क्लोन बनाता है[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |

### उदाहरण

यह उदाहरण छवि सतह पर आदिम आकार बनाने के लिए ग्राफिक्स वर्ग का उपयोग करता है। ऑपरेशन को प्रदर्शित करने के लिए, उदाहरण PSD प्रारूप में एक नई छवि बनाता है और ग्राफिक्स वर्ग द्वारा प्रदर्शित ड्रा विधियों का उपयोग करके छवि सतह पर आदिम आकृतियों को खींचता है और फिर इसे PSD फ़ाइल प्रारूप में निर्यात करता है।

```csharp
[C#]

// छवि का एक उदाहरण बनाएं 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स क्लास का एक उदाहरण बनाएं और आरंभ करें
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // स्पष्ट ग्राफिक्स सतह
    graphics.Clear(Color.Wheat);

    // ब्लैक कलर वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक आर्क बनाएं, 
    // आर्क के चारों ओर एक आयत, स्टार्ट एंगल और स्वीप एंगल
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // ब्लू कलर और को-ऑर्डिनेट पॉइंट वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक बेज़ियर ड्रा करें।
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // हरे रंग और बिंदुओं की एक सरणी वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक वक्र बनाएं
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // पेन ऑब्जेक्ट और आसपास के आयत का उपयोग करके एक दीर्घवृत्त बनाएं
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //एक रेखा खींचो 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // पाई सेगमेंट ड्रा करें
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // पेन ऑब्जेक्ट को लाल रंग और बिंदुओं की एक सरणी निर्दिष्ट करके एक बहुभुज बनाएं
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // एक आयत बनाएं
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    // एक सॉलिडब्रश ऑब्जेक्ट बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // विशिष्ट बिंदु पर सॉलिडब्रश ऑब्जेक्ट और फ़ॉन्ट का उपयोग करके एक स्ट्रिंग बनाएं
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions का एक उदाहरण बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // सभी परिवर्तनों को सहेजें।
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### यह सभी देखें

* class [Brush](../../aspose.psd/brush/)
* नाम स्थान [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* सभा [Aspose.PSD](../../)


