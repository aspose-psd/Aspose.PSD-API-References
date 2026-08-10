---
title: "Graphics.FillClosedCurve"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। एक पॉइंटF संरचनाओं की एरे द्वारा परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 और वैकल्पिक फ़िल मोड का उपयोग करता है।"
type: docs
weight: 350
url: /hi/net/aspose.psd/graphics/fillclosedcurve/
---
{{< psd/tize >}}
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

एक एरे में मौजूद [`PointF`](../../pointf/) संरचनाओं द्वारा परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 और वैकल्पिक फ़िल मोड का उपयोग करता है।

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | PointF[] | [`PointF`](../../pointf/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -or- *points* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

निर्दिष्ट फ़िल मोड का उपयोग करके एक एरे में मौजूद [`PointF`](../../pointf/) संरचनाओं द्वारा परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 का उपयोग करता है।

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | PointF[] | [`PointF`](../../pointf/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | FillMode | [`FillMode`](../../fillmode/) एनीमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -or- *points* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

निर्दिष्ट फ़िल मोड और टेंशन का उपयोग करके एक एरे में मौजूद [`PointF`](../../pointf/) संरचनाओं द्वारा परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है।

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | एक [`Brush`](../../brush/) जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | PointF[] | [`PointF`](../../pointf/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | FillMode | [`FillMode`](../../fillmode/) एनीमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |
| तनाव | Single | 0.0F या उससे अधिक का मान जो वक्र की टेंशन को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -or- *points* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

एक एरे में मौजूद [`Point`](../../point/) संरचनाओं द्वारा परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 और वैकल्पिक फ़िल मोड का उपयोग करता है।

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | Point[] | [`Point`](../../point/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -or- *points* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

निर्दिष्ट फ़िल मोड का उपयोग करके एक एरे में मौजूद [`Point`](../../point/) संरचनाओं द्वारा परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 का उपयोग करता है।

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | Point[] | [`Point`](../../point/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | FillMode | [`FillMode`](../../fillmode/) एनीमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -or- *points* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

निर्दिष्ट फ़िल मोड और टेंशन का उपयोग करके एक एरे में मौजूद [`Point`](../../point/) संरचनाओं द्वारा परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है।

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| points | Point[] | [`Point`](../../point/) संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | FillMode | [`FillMode`](../../fillmode/) एनीमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |
| तनाव | Single | 0.0F या उससे अधिक का मान जो वक्र की टेंशन को निर्दिष्ट करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। -or- *points* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


