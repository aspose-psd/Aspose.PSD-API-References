---
title: Graphics.DrawCurve
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Graphics तरक. क एक नर्दष्ट सरण के मध्यम से एक कर्डनल स्पलइन बनत हैPointF संरचनएं यह वध 0.5. के डफ़ल्ट तनव क उपयग करत है
type: docs
weight: 200
url: /hi/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../../pointf/) संरचनाएं। यह विधि 0.5. के डिफ़ॉल्ट तनाव का उपयोग करती है

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और ऊंचाई को निर्धारित करता है। |
| points | PointF[] | की श्रंखला[`PointF`](../../pointf/) संरचनाएं जो पट्टी को परिभाषित करती हैं। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../../pointf/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं।

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और ऊंचाई को निर्धारित करता है। |
| points | PointF[] | की श्रंखला[`PointF`](../../pointf/) संरचनाएं जो वक्र को परिभाषित करने वाले बिंदुओं का प्रतिनिधित्व करती हैं। |
| tension | Single | 0.0F से अधिक या उसके बराबर मान जो वक्र के तनाव को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../../pointf/) संरचनाएं। आरेखण सरणी की शुरुआत से ऑफसेट शुरू होता है। यह विधि 0.5. के डिफ़ॉल्ट तनाव का उपयोग करती है

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और ऊंचाई को निर्धारित करता है। |
| points | PointF[] | की श्रंखला[`PointF`](../../pointf/) संरचनाएं जो पट्टी को परिभाषित करती हैं। |
| offset | Int32 | के सरणी में पहले तत्व से ऑफसेट*points* वक्र में प्रारंभिक बिंदु के लिए पैरामीटर। |
| numberOfSegments | Int32 | वक्र में शामिल करने के लिए प्रारंभिक बिंदु के बाद खंडों की संख्या। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../../pointf/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं। आरेखण सरणी की शुरुआत से ऑफ़सेट प्रारंभ होता है.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और ऊंचाई को निर्धारित करता है। |
| points | PointF[] | की श्रंखला[`PointF`](../../pointf/) संरचनाएं जो पट्टी को परिभाषित करती हैं। |
| offset | Int32 | के सरणी में पहले तत्व से ऑफसेट*points* वक्र में प्रारंभिक बिंदु के लिए पैरामीटर। |
| numberOfSegments | Int32 | वक्र में शामिल करने के लिए प्रारंभिक बिंदु के बाद खंडों की संख्या। |
| tension | Single | 0.0F से अधिक या उसके बराबर मान जो वक्र के तनाव को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`Point`](../../point/) संरचनाएं.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और ऊंचाई को निर्धारित करता है। |
| points | Point[] | की श्रंखला[`Point`](../../point/) संरचनाएं जो पट्टी को परिभाषित करती हैं। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`Point`](../../point/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं।

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और ऊंचाई को निर्धारित करता है। |
| points | Point[] | की श्रंखला[`Point`](../../point/) संरचनाएं जो पट्टी को परिभाषित करती हैं। |
| tension | Single | 0.0F से अधिक या उसके बराबर मान जो वक्र के तनाव को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`Point`](../../point/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं।

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और ऊंचाई को निर्धारित करता है। |
| points | Point[] | की श्रंखला[`Point`](../../point/) संरचनाएं जो पट्टी को परिभाषित करती हैं। |
| offset | Int32 | के सरणी में पहले तत्व से ऑफसेट*points* वक्र में प्रारंभिक बिंदु के लिए पैरामीटर। |
| numberOfSegments | Int32 | वक्र में शामिल करने के लिए प्रारंभिक बिंदु के बाद खंडों की संख्या। |
| tension | Single | 0.0F से अधिक या उसके बराबर मान जो वक्र के तनाव को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)


