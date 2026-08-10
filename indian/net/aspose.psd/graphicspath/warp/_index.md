---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GraphicsPath विधि। एक आयत और एक समानांतर चतुर्भुज द्वारा परिभाषित वॉर्प ट्रांसफ़ॉर्म को इस GraphicsPath पर लागू करता है।"
type: docs
weight: 180
url: /hi/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

एक आयत और एक समानांतर चतुर्भुज द्वारा परिभाषित वॉर्प ट्रांसफ़ॉर्म को इस [`GraphicsPath`](../) पर लागू करता है।

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| destPoints | PointF[] | एक एरे जिसमें [`PointF`](../../pointf/) संरचनाएँ होती हैं जो एक समानांतर चतुर्भुज को परिभाषित करती हैं, जिसमें *srcRect* द्वारा परिभाषित आयत को रूपांतरित किया जाता है। एरे में तीन या चार तत्व हो सकते हैं। यदि एरे में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला‑दायाँ कोना पहले तीन बिंदुओं द्वारा संकेतित होता है। |
| srcRect | RectangleF | एक [`RectangleF`](../../rectanglef/) जो वह आयत दर्शाता है जिसे *destPoints* द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |

### देखें भी

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

एक आयत और एक समानांतर चतुर्भुज द्वारा परिभाषित वॉर्प ट्रांसफ़ॉर्म को इस [`GraphicsPath`](../) पर लागू करता है।

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| destPoints | PointF[] | एक एरे जिसमें [`PointF`](../../pointf/) संरचनाएँ होती हैं जो एक समानांतर चतुर्भुज को परिभाषित करती हैं, जिसमें *srcRect* द्वारा परिभाषित आयत को रूपांतरित किया जाता है। एरे में तीन या चार तत्व हो सकते हैं। यदि एरे में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला‑दायाँ कोना पहले तीन बिंदुओं द्वारा संकेतित होता है। |
| srcRect | RectangleF | एक [`RectangleF`](../../rectanglef/) जो वह आयत दर्शाता है जिसे *destPoints* द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |
| matrix | Matrix | एक [`Matrix`](../../matrix/) जो पथ पर लागू करने के लिए एक ज्यामितीय रूपांतरण निर्दिष्ट करता है। |

### देखें भी

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

एक आयत और एक समानांतर चतुर्भुज द्वारा परिभाषित वॉर्प ट्रांसफ़ॉर्म को इस [`GraphicsPath`](../) पर लागू करता है।

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| destPoints | PointF[] | एक एरे जिसमें [`PointF`](../../pointf/) संरचनाएँ होती हैं जो एक समानांतर चतुर्भुज को परिभाषित करती हैं, जिसमें *srcRect* द्वारा परिभाषित आयत को रूपांतरित किया जाता है। एरे में तीन या चार तत्व हो सकते हैं। यदि एरे में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला‑दायाँ कोना पहले तीन बिंदुओं द्वारा संकेतित होता है। |
| srcRect | RectangleF | एक [`RectangleF`](../../rectanglef/) जो वह आयत दर्शाता है जिसे *destPoints* द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |
| matrix | Matrix | एक [`Matrix`](../../matrix/) जो पथ पर लागू करने के लिए एक ज्यामितीय रूपांतरण निर्दिष्ट करता है। |
| warpMode | WarpMode | एक [`WarpMode`](../../warpmode/) एनीमरेशन जो यह निर्दिष्ट करता है कि यह वॉर्प ऑपरेशन परिप्रेक्ष्य या द्विरैखिक मोड का उपयोग करता है। |

### देखें भी

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

एक आयत और एक समानांतर चतुर्भुज द्वारा परिभाषित वॉर्प ट्रांसफ़ॉर्म को इस [`GraphicsPath`](../) पर लागू करता है।

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| destPoints | PointF[] | एक एरे जिसमें [`PointF`](../../pointf/) संरचनाएँ होती हैं जो एक समानांतर चतुर्भुज को परिभाषित करती हैं, जिसमें *srcRect* द्वारा परिभाषित आयत को रूपांतरित किया जाता है। एरे में तीन या चार तत्व हो सकते हैं। यदि एरे में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला‑दायाँ कोना पहले तीन बिंदुओं द्वारा संकेतित होता है। |
| srcRect | RectangleF | एक [`RectangleF`](../../rectanglef/) जो वह आयत दर्शाता है जिसे *destPoints* द्वारा परिभाषित समानांतर चतुर्भुज में रूपांतरित किया जाता है। |
| matrix | Matrix | एक [`Matrix`](../../matrix/) जो पथ पर लागू करने के लिए एक ज्यामितीय रूपांतरण निर्दिष्ट करता है। |
| warpMode | WarpMode | एक [`WarpMode`](../../warpmode/) एनीमरेशन जो यह निर्दिष्ट करता है कि यह वॉर्प ऑपरेशन परिप्रेक्ष्य या द्विरैखिक मोड का उपयोग करता है। |
| flatness | Single | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि परिणामी पथ कितना सपाट है। अधिक जानकारी के लिए, देखें [`Flatten`](../flatten/) मेथड्स। |

### देखें भी

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


