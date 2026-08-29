---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। निर्दिष्ट PointF संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 का उपयोग करता है।"
type: docs
weight: 210
url: /hi/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

निर्दिष्ट [`PointF`](../../pointf/) संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 का उपयोग करता है।

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र का रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | PointF[] | [`PointF`](../../pointf/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

निर्दिष्ट टेंशन का उपयोग करके, निर्दिष्ट [`PointF`](../../pointf/) संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है।

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र का रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | PointF[] | [`PointF`](../../pointf/) संरचनाओं की एरे जो उन बिंदुओं को दर्शाती है जो वक्र को परिभाषित करती हैं। |
| तनाव | Single | 0.0F या उससे अधिक का मान जो वक्र की टेंशन को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

निर्दिष्ट [`PointF`](../../pointf/) संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है। ड्राइंग एरे की शुरुआत से ऑफसेट होकर शुरू होती है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 का उपयोग करता है।

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र का रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | PointF[] | [`PointF`](../../pointf/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| offset | Int32 | *points* पैरामीटर की एरे के पहले तत्व से वक्र के प्रारंभ बिंदु तक का ऑफसेट। |
| numberOfSegments | Int32 | वक्र में शामिल करने के लिए प्रारंभ बिंदु के बाद के सेगमेंटों की संख्या। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

निर्दिष्ट टेंशन का उपयोग करके, निर्दिष्ट [`PointF`](../../pointf/) संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है। ड्राइंग एरे की शुरुआत से ऑफसेट होकर शुरू होती है।

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र का रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | PointF[] | [`PointF`](../../pointf/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| offset | Int32 | *points* पैरामीटर की एरे के पहले तत्व से वक्र के प्रारंभ बिंदु तक का ऑफसेट। |
| numberOfSegments | Int32 | वक्र में शामिल करने के लिए प्रारंभ बिंदु के बाद के सेगमेंटों की संख्या। |
| तनाव | Single | 0.0F या उससे अधिक का मान जो वक्र की टेंशन को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

निर्दिष्ट [`Point`](../../point/) संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है।

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र का रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | Point[] | [`Point`](../../point/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

निर्दिष्ट टेंशन का उपयोग करके, निर्दिष्ट [`Point`](../../point/) संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है।

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र का रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | Point[] | [`Point`](../../point/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| तनाव | Single | 0.0F या उससे अधिक का मान जो वक्र की टेंशन को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

निर्दिष्ट टेंशन का उपयोग करके, निर्दिष्ट [`Point`](../../point/) संरचनाओं की एरे के माध्यम से एक कार्डिनल स्प्लाइन बनाता है।

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र का रंग, चौड़ाई और ऊँचाई निर्धारित करता है। |
| points | Point[] | [`Point`](../../point/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| offset | Int32 | *points* पैरामीटर की एरे के पहले तत्व से वक्र के प्रारंभ बिंदु तक का ऑफसेट। |
| numberOfSegments | Int32 | वक्र में शामिल करने के लिए प्रारंभ बिंदु के बाद के सेगमेंटों की संख्या। |
| तनाव | Single | 0.0F या उससे अधिक का मान जो वक्र की टेंशन को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


