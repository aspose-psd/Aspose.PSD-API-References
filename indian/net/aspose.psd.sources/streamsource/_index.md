---
title: "क्लास StreamSource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Sources.StreamSource क्लास। एक स्ट्रीम स्रोत का प्रतिनिधित्व करता है।"
type: docs
weight: 6120
url: /hi/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

स्ट्रीम स्रोत को दर्शाता है।

```csharp
public sealed class StreamSource : Source
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | `StreamSource` क्लास का नया उदाहरण प्रारंभ करता है। |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | `StreamSource` क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि कंटेनर नष्ट होने पर स्ट्रीम को नष्ट किया जाना चाहिए या नहीं। |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | स्ट्रीम प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | स्ट्रीम कंटेनर प्राप्त करता है। |

## उदाहरण

यह उदाहरण इमेज सतह पर मूल आकार बनाने के लिए Graphics क्लास का उपयोग करता है। संचालन को प्रदर्शित करने के लिए, उदाहरण PSD प्रारूप में एक नई इमेज बनाता है और Graphics क्लास द्वारा प्रदत्त Draw विधियों का उपयोग करके इमेज सतह पर मूल आकार खींचता है, फिर इसे PSD फ़ाइल प्रारूप में निर्यात करता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाएं।
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाएं और प्रारंभ करें।
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करें।
    graphics.Clear(Color.Wheat);

    //काली रंग वाले Pen ऑब्जेक्ट को निर्दिष्ट करके एक आर्क ड्रॉ करें, 
    //आर्क को घेरने वाला एक आयत, प्रारंभिक कोण और स्वीप कोण
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //नीले रंग वाले Pen ऑब्जेक्ट और निर्देशांक बिंदुओं को निर्दिष्ट करके एक बीज़ियर ड्रॉ करें।
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //हरे रंग वाले Pen ऑब्जेक्ट और बिंदुओं की एक श्रृंखला को निर्दिष्ट करके एक कर्व ड्रॉ करें
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen ऑब्जेक्ट और एक घेरने वाले आयत का उपयोग करके एक अंडाकार ड्रॉ करें
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //एक रेखा ड्रॉ करें 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //एक पाई सेगमेंट ड्रॉ करें
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //लाल रंग वाले Pen ऑब्जेक्ट और बिंदुओं की एक श्रृंखला को निर्दिष्ट करके एक बहुभुज ड्रॉ करें
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //एक आयत ड्रॉ करें
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //एक SolidBrush ऑब्जेक्ट बनाएं और उसकी विभिन्न गुण सेट करें
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush ऑब्जेक्ट और फ़ॉन्ट का उपयोग करके, विशिष्ट बिंदु पर एक स्ट्रिंग ड्रॉ करें
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions का एक उदाहरण बनाएं और उसकी विभिन्न गुण सेट करें
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // सभी परिवर्तन सहेजें।
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### देखें भी

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


