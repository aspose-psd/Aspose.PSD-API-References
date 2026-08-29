---
title: "Region.Equals"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Region मेथड। परीक्षण करता है कि क्या निर्दिष्ट Region इस Region के समान है निर्दिष्ट ड्रॉइंग सतह पर"
type: docs
weight: 40
url: /hi/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

परीक्षण करता है कि निर्दिष्ट [`Region`](../) इस [`Region`](../) के समान है निर्दिष्ट ड्रॉइंग सतह पर।

```csharp
public bool Equals(Region region, Graphics g)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| region | Region | परीक्षण के लिए [`Region`](../)। |
| g | Graphics | एक [`Graphics`](../../graphics/) जो ड्राइंग सतह का प्रतिनिधित्व करता है। |

### रिटर्न वैल्यू

यदि region का आंतरिक भाग इस region के आंतरिक भाग के समान है जब *g* पैरामीटर के साथ जुड़े परिवर्तन लागू किया जाता है तो True; अन्यथा false।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *g *or* region* शून्य है। |

### देखें भी

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

जाँचें कि ऑब्जेक्ट समान हैं या नहीं।

```csharp
public override bool Equals(object obj)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| obj | ऑब्जेक्ट | दूसरा ऑब्जेक्ट। |

### रिटर्न वैल्यू

समानता तुलना परिणाम।

### देखें भी

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


