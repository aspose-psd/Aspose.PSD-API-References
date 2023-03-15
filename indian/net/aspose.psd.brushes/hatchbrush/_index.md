---
title: Class HatchBrush
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Brushes.HatchBrush कक्ष. हैच स्टइल अग्रभूम रंग और पृष्ठभूम रंग के सथ आयतकर ब्रश क परभषत करत है इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 130
url: /hi/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

हैच स्टाइल, अग्रभूमि रंग और पृष्ठभूमि रंग के साथ आयताकार ब्रश को परिभाषित करता है। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class HatchBrush : Brush
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [HatchBrush](hatchbrush/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | हैच लाइनों के बीच रिक्त स्थान का रंग प्राप्त या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | हैच लाइन का रंग प्राप्त या सेट करता है। |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | इस ब्रश की हैच स्टाइल प्राप्त या सेट करता है। |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ब्रश अपारदर्शिता प्राप्त या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 के मान का अर्थ है कि ब्रश पूरी तरह से दिखाई दे रहा है, 1 के मान का अर्थ है कि ब्रश पूरी तरह से अपारदर्शी है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | वर्तमान का एक नया गहरा क्लोन बनाता है[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |

### उदाहरण

यह उदाहरण पेन ऑब्जेक्ट्स का निर्माण और उपयोग दिखाता है। उदाहरण एक नई छवि बनाता है और छवि की सतह पर आयत बनाता है।

```csharp
[C#]

// छवि का एक उदाहरण बनाएं
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स का एक उदाहरण बनाएं और इसे इमेज ऑब्जेक्ट के साथ इनिशियलाइज़ करें
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // ग्राफिक्स सतह को सफेद रंग से साफ करें
    graphics.Clear(Aspose.PSD.Color.White);

    // रंग लाल और चौड़ाई 5 के साथ पेन का एक उदाहरण बनाएं
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    // हैचब्रश का एक उदाहरण बनाएं और इसके गुण सेट करें
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    // पेन का एक उदाहरण बनाएँ
    // इसे हैचब्रश ऑब्जेक्ट और चौड़ाई के साथ आरंभ करें
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // पेन ऑब्जेक्ट निर्दिष्ट करके आयत बनाएं
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // पेन ऑब्जेक्ट निर्दिष्ट करके आयत बनाएं
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // निर्यात विकल्प बनाएं और उन्हें प्रारंभ करें।
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // सभी परिवर्तनों को सहेजें।
    image.Save("c:\\temp\\output.jp2", options);
}
```

### यह सभी देखें

* class [Brush](../../aspose.psd/brush/)
* नाम स्थान [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* सभा [Aspose.PSD](../../)


