---
title: "क्लास HatchBrush"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Brushes.HatchBrush क्लास। एक आयताकार ब्रश को परिभाषित करता है जिसमें एक हैच शैली, अग्रभूमि रंग और पृष्ठभूमि रंग होते हैं। इस क्लास को विरासत में नहीं लिया जा सकता।"
type: docs
weight: 130
url: /hi/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

हैच शैली, अग्रभूमि रंग और पृष्ठभूमि रंग के साथ एक आयताकार ब्रश को परिभाषित करता है। यह क्लास विरासत में नहीं ली जा सकती।

```csharp
public sealed class HatchBrush : Brush
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [HatchBrush](hatchbrush/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | हैच लाइनों के बीच के अंतराल का रंग प्राप्त करता है या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | हैच लाइनों का रंग प्राप्त करता है या सेट करता है। |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | इस ब्रश की हैच शैली प्राप्त करता है या सेट करता है। |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश की अपारदर्शिता प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह से दिखाई देता है, 1 का मान मतलब ब्रश पूरी तरह से अपारदर्शी है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | वर्तमान [`Brush`](../../aspose.psd/brush/) की एक नई डीप क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |

## उदाहरण

यह उदाहरण Pen ऑब्जेक्ट्स के निर्माण और उपयोग को दिखाता है। उदाहरण एक नई Image बनाता है और Image सतह पर Rectangles खींचता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाएँ।
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics का एक उदाहरण बनाएं और इसे Image ऑब्जेक्ट के साथ प्रारंभ करें।
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को White Color से साफ़ करें।
    graphics.Clear(Aspose.PSD.Color.White);

    //Pen का एक उदाहरण बनाएं, रंग Red और चौड़ाई 5 के साथ।
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush का एक उदाहरण बनाएं और उसकी गुण सेट करें।
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Pen का एक उदाहरण बनाएं।
    //इसे HatchBrush ऑब्जेक्ट और चौड़ाई के साथ प्रारंभ करें।
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Pen ऑब्जेक्ट निर्दिष्ट करके Rectangles खींचें।
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Pen ऑब्जेक्ट निर्दिष्ट करके Rectangles खींचें।
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // निर्यात विकल्प बनाएं और उन्हें प्रारंभ करें।
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // सभी परिवर्तन सहेजें।
    image.Save("c:\\temp\\output.jp2", options);
}
```

### देखें भी

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


