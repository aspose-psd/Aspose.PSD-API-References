---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GraphicsPath मेथड। इस पाथ में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में बदलता है"
type: docs
weight: 90
url: /hi/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

इस पथ में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में बदलता है।

```csharp
public void Flatten()
```

### देखें भी

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

निर्दिष्ट ट्रांसफ़ॉर्म लागू करता है और फिर इस [`GraphicsPath`](../) में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में बदलता है।

```csharp
public void Flatten(Matrix matrix)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| matrix | Matrix | एक [`Matrix`](../../matrix/) जिससे इस [`GraphicsPath`](../) को फ्लैटन करने से पहले ट्रांसफ़ॉर्म किया जाता है। |

### देखें भी

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

इस [`GraphicsPath`](../) में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में बदलता है।

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| matrix | Matrix | एक [`Matrix`](../../matrix/) जिससे इस [`GraphicsPath`](../) को फ्लैटन करने से पहले ट्रांसफ़ॉर्म किया जाता है। |
| समतलता | Single | वक्र और उसके फ्लैटन किए गए अनुमान के बीच अधिकतम अनुमत त्रुटि को निर्दिष्ट करता है। 0.25 का मान डिफ़ॉल्ट है। फ्लैटननेस मान को कम करने से अनुमान में रेखा खंडों की संख्या बढ़ेगी। |

### देखें भी

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


