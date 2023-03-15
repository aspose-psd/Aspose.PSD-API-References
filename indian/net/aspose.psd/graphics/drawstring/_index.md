---
title: Graphics.DrawString
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Graphics तरक. नर्दष्ट पठ स्ट्रंग क नर्दष्ट स्थन पर नर्दष्ट के सथ आरेखत करत हैBrush औरFont वस्तुओं.
type: docs
weight: 320
url: /hi/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../../brush/) और[`Font`](../../font/) वस्तुओं.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | String | खींचने के लिए तार। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो खींचे गए पाठ के रंग और बनावट को निर्धारित करता है। |
| x | Single | खींचे गए पाठ के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Single | खींचे गए पाठ के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -या- *s* शून्य है। |

### यह सभी देखें

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../../brush/) और[`Font`](../../font/) वस्तुओं.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | String | खींचने के लिए तार। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो खींचे गए पाठ के रंग और बनावट को निर्धारित करता है। |
| point | PointF | [`PointF`](../../pointf/) संरचना जो खींचे गए पाठ के ऊपरी-बाएँ कोने को निर्दिष्ट करती है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -या- *s* शून्य है। |

### उदाहरण

यह उदाहरण छवि सतह पर तार खींचने के लिए फ़ॉन्ट और सॉलिडब्रश वर्ग के उपयोग को प्रदर्शित करता है। उदाहरण एक नई छवि बनाता है और आंकड़े और ग्राफिक्सपाथ का उपयोग करके आकृतियाँ बनाता है

```csharp
[C#]

// छवि का एक उदाहरण बनाता है
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स वर्ग का एक उदाहरण बनाता है और आरंभ करता है
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // ग्राफिक्स की सतह को साफ करता है
    graphics.Clear(Color.Wheat);

    // फ़ॉन्ट का एक उदाहरण बनाता है
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // लाल रंग वाले सॉलिडब्रश का एक उदाहरण बनाएं
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // एक स्ट्रिंग ड्रा करें
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // निर्यात विकल्प बनाएँ।
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // सभी परिवर्तनों को सहेजें
    image.Save("C:\\temp\\output.gif", options);
}
```

### यह सभी देखें

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../../brush/) और[`Font`](../../font/) निर्दिष्ट स्वरूपण विशेषताओं का उपयोग करके ऑब्जेक्ट[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | String | खींचने के लिए तार। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो खींचे गए पाठ के रंग और बनावट को निर्धारित करता है। |
| x | Single | खींचे गए पाठ के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Single | खींचे गए पाठ के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| format | StringFormat | [`StringFormat`](../../stringformat/) जो प्रारूपण विशेषताओं को निर्दिष्ट करता है, जैसे पंक्ति रिक्ति और संरेखण, जो आरेखित पाठ पर लागू होते हैं। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -या- *s* शून्य है। |

### यह सभी देखें

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../../brush/) और[`Font`](../../font/) निर्दिष्ट स्वरूपण विशेषताओं का उपयोग करके ऑब्जेक्ट[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | String | खींचने के लिए तार। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो खींचे गए पाठ के रंग और बनावट को निर्धारित करता है। |
| point | PointF | [`PointF`](../../pointf/) संरचना जो खींचे गए पाठ के ऊपरी-बाएँ कोने को निर्दिष्ट करती है। |
| format | StringFormat | [`StringFormat`](../../stringformat/) जो प्रारूपण विशेषताओं को निर्दिष्ट करता है, जैसे पंक्ति रिक्ति और संरेखण, जो आरेखित पाठ पर लागू होते हैं। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -या- *s* शून्य है। |

### यह सभी देखें

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट आयत में निर्दिष्ट के साथ आरेखित करता है[`Brush`](../../brush/) और[`Font`](../../font/) वस्तुओं.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | String | खींचने के लिए तार। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो खींचे गए पाठ के रंग और बनावट को निर्धारित करता है। |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) संरचना जो खींचे गए पाठ के स्थान को निर्दिष्ट करती है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -या- *s* शून्य है। |

### यह सभी देखें

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट आयत में निर्दिष्ट के साथ आरेखित करता है[`Brush`](../../brush/) और[`Font`](../../font/) निर्दिष्ट स्वरूपण विशेषताओं का उपयोग करके ऑब्जेक्ट[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | String | खींचने के लिए तार। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो खींचे गए पाठ के रंग और बनावट को निर्धारित करता है। |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) संरचना जो खींचे गए पाठ के स्थान को निर्दिष्ट करती है। |
| format | StringFormat | [`StringFormat`](../../stringformat/) जो प्रारूपण विशेषताओं को निर्दिष्ट करता है, जैसे पंक्ति रिक्ति और संरेखण, जो आरेखित पाठ पर लागू होते हैं। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -या- *s* शून्य है। -या- *brush* शून्य है। |

### यह सभी देखें

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)


