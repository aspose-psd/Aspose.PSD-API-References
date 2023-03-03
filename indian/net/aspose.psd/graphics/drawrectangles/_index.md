---
title: Graphics.DrawRectangles
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Graphics तरक. नर्दष्ट आयतं क एक श्रृंखल बनत हैRectangleF संरचनएं.
type: docs
weight: 310
url: /hi/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

निर्दिष्ट आयतों की एक श्रृंखला बनाता है[`RectangleF`](../../rectanglef/) संरचनाएं.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आयतों की रूपरेखा के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| rects | RectangleF[] | की श्रंखला[`RectangleF`](../../rectanglef/) संरचनाएं जो आकर्षित करने के लिए आयतों का प्रतिनिधित्व करती हैं। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *rects* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

निर्दिष्ट आयतों की एक श्रृंखला बनाता है[`Rectangle`](../../rectangle/) संरचनाएं.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आयतों की रूपरेखा के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| rects | Rectangle[] | की श्रंखला[`Rectangle`](../../rectangle/) संरचनाएं जो आकर्षित करने के लिए आयतों का प्रतिनिधित्व करती हैं। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *rects* शून्य है। |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)


