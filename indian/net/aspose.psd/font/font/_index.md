---
title: "Font.Font"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Font कन्स्ट्रक्टर। निर्दिष्ट मौजूदा Font और FontStyle एनेमरेशन का उपयोग करने वाला नया Font प्रारंभ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

एक नया [`Font`](../) प्रारंभ करता है जो निर्दिष्ट मौजूदा [`Font`](../) और [`FontStyle`](../../fontstyle/) एनेमरेशन का उपयोग करता है।

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| prototype | Font | वह मौजूदा [`Font`](../) जिससे नया [`Font`](../) बनाया जाएगा। |
| newStyle | FontStyle | नए [`Font`](../) पर लागू करने के लिए [`FontStyle`](../../fontstyle/)। [`FontStyle`](../../fontstyle/) एनेमरेशन के कई मानों को OR ऑपरेटर के साथ जोड़ा जा सकता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *prototype* शून्य है। |

### देखें भी

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

निर्दिष्ट आकार का उपयोग करके नया [`Font`](../) प्रारंभ करता है। कैरेक्टर सेट को Default, ग्राफ़िक्स यूनिट को Point, फ़ॉन्ट स्टाइल को Regular पर सेट किया जाता है।

```csharp
public Font(string fontName, float emSize)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | String | [`Font`](../) नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | Single | नए फ़ॉन्ट का em-size, पॉइंट्स में। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या बराबर है, अनंत के बराबर है या वैध संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### देखें भी

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

निर्दिष्ट आकार और शैली का उपयोग करके नया [`Font`](../) प्रारंभ करता है। कैरेक्टर सेट को Default, ग्राफ़िक्स यूनिट को Point पर सेट किया जाता है।

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | String | [`Font`](../) नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | Single | नए फ़ॉन्ट का em-size, पॉइंट्स में। |
| style | FontStyle | नए फ़ॉन्ट का [`FontStyle`](../../fontstyle/)। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या बराबर है, अनंत के बराबर है या वैध संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### देखें भी

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

निर्दिष्ट आकार और इकाई का उपयोग करके नया [`Font`](../) प्रारंभ करता है। कैरेक्टर सेट को Default, शैली को Regular पर सेट किया जाता है।

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | String | [`Font`](../) नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | Single | नए फ़ॉन्ट का em-size, *unit* पैरामीटर द्वारा निर्दिष्ट इकाइयों में। |
| unit | GraphicsUnit | नए फ़ॉन्ट का [`GraphicsUnit`](../../graphicsunit/)। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या बराबर है, अनंत के बराबर है या वैध संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### देखें भी

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

निर्दिष्ट आकार, शैली, इकाई और कैरेक्टर सेट का उपयोग करके नया [`Font`](../) प्रारंभ करता है।

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | String | [`Font`](../) नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | Single | नए फ़ॉन्ट का em-size, *unit* पैरामीटर द्वारा निर्दिष्ट इकाइयों में। |
| style | FontStyle | नए फ़ॉन्ट का [`FontStyle`](../../fontstyle/)। |
| unit | GraphicsUnit | नए फ़ॉन्ट का [`GraphicsUnit`](../../graphicsunit/)। |
| characterSet | CharacterSet | इस फ़ॉन्ट के लिए उपयोग करने वाला कैरेक्टर सेट। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या बराबर है, अनंत के बराबर है या वैध संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### देखें भी

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

निर्दिष्ट आकार, शैली और इकाई का उपयोग करके नया [`Font`](../) प्रारंभ करता है।

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | String | [`Font`](../) नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | Single | नए फ़ॉन्ट का em-size, *unit* पैरामीटर द्वारा निर्दिष्ट इकाइयों में। |
| style | FontStyle | नए फ़ॉन्ट का [`FontStyle`](../../fontstyle/)। |
| unit | GraphicsUnit | नए फ़ॉन्ट का [`GraphicsUnit`](../../graphicsunit/)। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या बराबर है, अनंत के बराबर है या वैध संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### देखें भी

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


