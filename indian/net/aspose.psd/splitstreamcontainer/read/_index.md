---
title: "SplitStreamContainer.Read"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "SplitStreamContainer मेथड। निर्दिष्ट बाइट बफ़र को भरने के लिए बाइट्स पढ़ता है।"
type: docs
weight: 110
url: /hi/net/aspose.psd/splitstreamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

निर्दिष्ट बाइट बफ़र को भरने के लिए बाइट्स पढ़ता है।

```csharp
public override int Read(byte[] bytes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| बाइट्स | Byte[] | भरने के लिए बाइट्स। |

### रिटर्न वैल्यू

पढ़े गए बाइट्स की संख्या। यदि स्ट्रीम में पर्याप्त बाइट्स नहीं हैं तो यह मान बफ़र में बाइट्स की संख्या से कम हो सकता है।

### देखें भी

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है।

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| बफ़र | Byte[] | बाइट्स की एक एरे। जब यह मेथड रिटर्न करता है, बफ़र में निर्दिष्ट बाइट एरे होती है जिसमें *offset* और (*offset* + *count* - 1) के बीच के मान वर्तमान स्रोत से पढ़े गए बाइट्स द्वारा प्रतिस्थापित होते हैं। |
| offset | Int32 | वर्तमान स्ट्रीम से पढ़े गए डेटा को संग्रहीत करना शुरू करने के लिए *buffer* में शून्य-आधारित बाइट ऑफसेट। |
| count | Int32 | वर्तमान स्ट्रीम से पढ़े जाने वाले बाइट्स की अधिकतम संख्या। |

### रिटर्न वैल्यू

बफ़र में पढ़े गए बाइट्स की कुल संख्या। यदि अनुरोधित बाइट्स उपलब्ध नहीं हैं तो यह अनुरोधित बाइट्स की संख्या से कम हो सकता है, या यदि स्ट्रीम का अंत पहुंच गया हो तो शून्य (0) हो सकता है।

### देखें भी

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


