---
title: "Graphics.DrawString"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट Brush और Font ऑब्जेक्ट्स के साथ ड्रॉ करता है।"
type: docs
weight: 330
url: /hi/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट [`Brush`](../../brush/) और [`Font`](../../font/) ऑब्जेक्ट्स के साथ ड्रॉ करता है।

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| x | Single | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Single | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* null है। -or- *s* null है। |

### देखें भी

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट [`Brush`](../../brush/) और [`Font`](../../font/) ऑब्जेक्ट्स के साथ ड्रॉ करता है।

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| point | PointF | [`PointF`](../../pointf/) स्ट्रक्चर जो ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* null है। -or- *s* null है। |

## उदाहरण

यह उदाहरण फ़ॉन्ट और SolidBrush क्लास का उपयोग करके इमेज सतह पर स्ट्रिंग्स ड्रॉ करने को दर्शाता है। उदाहरण एक नई इमेज बनाता है और फ़िगर्स तथा GraphicsPath का उपयोग करके आकार ड्रॉ करता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाता है
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाता है और इनिशियलाइज़ करता है
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करता है
    graphics.Clear(Color.Wheat);

    //Font का एक इंस्टेंस बनाता है
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //लाल रंग वाला SolidBrush का एक इंस्टेंस बनाता है
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //एक स्ट्रिंग ड्रॉ करता है
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // एक्सपोर्ट विकल्प बनाता है।
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // सभी परिवर्तन सहेजें।
    image.Save("C:\\temp\\output.gif", options);
}
```

### देखें भी

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट [`Brush`](../../brush/) और [`Font`](../../font/) ऑब्जेक्ट्स का उपयोग करके, निर्दिष्ट [`StringFormat`](../../stringformat/) के फ़ॉर्मेटिंग एट्रिब्यूट्स के साथ ड्रॉ करता है।

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| x | Single | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Single | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| format | StringFormat | [`StringFormat`](../../stringformat/) जो फ़ॉर्मेटिंग एट्रिब्यूट्स, जैसे लाइन स्पेसिंग और अलाइनमेंट, को निर्दिष्ट करता है, जो ड्रॉ किए गए टेक्स्ट पर लागू होते हैं। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* null है। -or- *s* null है। |

### देखें भी

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट [`Brush`](../../brush/) और [`Font`](../../font/) ऑब्जेक्ट्स का उपयोग करके, निर्दिष्ट [`StringFormat`](../../stringformat/) के फ़ॉर्मेटिंग एट्रिब्यूट्स के साथ ड्रॉ करता है।

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| point | PointF | [`PointF`](../../pointf/) स्ट्रक्चर जो ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने को निर्दिष्ट करता है। |
| format | StringFormat | [`StringFormat`](../../stringformat/) जो फ़ॉर्मेटिंग एट्रिब्यूट्स, जैसे लाइन स्पेसिंग और अलाइनमेंट, को निर्दिष्ट करता है, जो ड्रॉ किए गए टेक्स्ट पर लागू होते हैं। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* null है। -or- *s* null है। |

### देखें भी

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट आयत में निर्दिष्ट [`Brush`](../../brush/) और [`Font`](../../font/) ऑब्जेक्ट्स के साथ ड्रॉ करता है।

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) स्ट्रक्चर जो ड्रॉ किए गए टेक्स्ट का स्थान निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* null है। -or- *s* null है। |

### देखें भी

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

निर्दिष्ट टेक्स्ट स्ट्रिंग को निर्दिष्ट आयत में निर्दिष्ट [`Brush`](../../brush/) और [`Font`](../../font/) ऑब्जेक्ट्स का उपयोग करके, निर्दिष्ट [`StringFormat`](../../stringformat/) के फ़ॉर्मेटिंग एट्रिब्यूट्स के साथ ड्रॉ करता है।

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| s | String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | Font | [`Font`](../../font/) जो स्ट्रिंग के टेक्स्ट फ़ॉर्मेट को परिभाषित करता है। |
| brush | Brush | [`Brush`](../../brush/) जो ड्रॉ किए गए टेक्स्ट का रंग और बनावट निर्धारित करता है। |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) स्ट्रक्चर जो ड्रॉ किए गए टेक्स्ट का स्थान निर्दिष्ट करता है। |
| format | StringFormat | [`StringFormat`](../../stringformat/) जो फ़ॉर्मेटिंग एट्रिब्यूट्स, जैसे लाइन स्पेसिंग और अलाइनमेंट, को निर्दिष्ट करता है, जो ड्रॉ किए गए टेक्स्ट पर लागू होते हैं। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* null है। -or- *s* null है। -or- *brush* null है। |

### देखें भी

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


