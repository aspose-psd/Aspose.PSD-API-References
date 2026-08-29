---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ImageAttributes विधि। रैप मोड सेट करती है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को किसी आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।"
type: docs
weight: 210
url: /hi/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

रैप मोड सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा होता है तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

```csharp
public void SetWrapMode(WrapMode mode)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mode | WrapMode | एक तत्व [`WrapMode`](../../wrapmode/) का जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |

### देखें भी

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा होता है तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mode | WrapMode | एक तत्व [`WrapMode`](../../wrapmode/) का जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| color | Color | एक [`ImageAttributes`](../) ऑब्जेक्ट जो रेंडर की गई छवि के बाहर के पिक्सेल का रंग निर्दिष्ट करता है। यह रंग तब दिखाई देता है जब मोड पैरामीटर को Clamp पर सेट किया जाता है और DrawImage को पास किया गया स्रोत आयत छवि से बड़ा होता है। |

### देखें भी

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा होता है तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mode | WrapMode | एक तत्व [`WrapMode`](../../wrapmode/) का जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| रंग | रंग | एक रंग ऑब्जेक्ट जो रेंडर की गई छवि के बाहर के पिक्सेल का रंग निर्दिष्ट करता है। यह रंग तब दिखाई देता है जब मोड पैरामीटर को Clamp पर सेट किया जाता है और DrawImage को पास किया गया स्रोत आयत छवि से बड़ा होता है। |
| क्लैंप | बूलियन | इस पैरामीटर का कोई प्रभाव नहीं है। इसे false पर सेट करें। |

### देखें भी

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


