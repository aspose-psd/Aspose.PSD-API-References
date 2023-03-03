---
title: Font.Font
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Font नर्मत. एक नय आरंभ करत हैFont ज नर्दष्ट मजूद क उपयग करत हैFont औरFontStyle गणन.
type: docs
weight: 10
url: /hi/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

एक नया आरंभ करता है[`Font`](../) जो निर्दिष्ट मौजूदा का उपयोग करता है[`Font`](../) और[`FontStyle`](../../fontstyle/) गणना.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prototype | Font | अस्तित्व[`Font`](../) जिससे नया बनाना है[`Font`](../). |
| newStyle | FontStyle | [`FontStyle`](../../fontstyle/) नए में आवेदन करने के लिए[`Font`](../) . के एकाधिक मान[`FontStyle`](../../fontstyle/) गणना को OR ऑपरेटर के साथ जोड़ा जा सकता है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *prototype* शून्य है। |

### यह सभी देखें

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* नाम स्थान [Aspose.PSD](../../font/)
* सभा [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

एक नया आरंभ करता है[`Font`](../) एक निर्दिष्ट आकार का उपयोग करना। वर्ण सेट पर सेट हैDefault , ग्राफिक्स यूनिट कोPoint , फ़ॉन्ट शैली toRegular .

```csharp
public Font(string fontName, float emSize)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | का एक स्ट्रिंग प्रतिनिधित्व[`Font`](../) नाम। |
| emSize | Single | नए फ़ॉन्ट का एम-आकार, बिंदुओं में। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या उसके बराबर है, अनंत का मूल्यांकन करता है या मान्य संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### यह सभी देखें

* class [Font](../)
* नाम स्थान [Aspose.PSD](../../font/)
* सभा [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

एक नया आरंभ करता है[`Font`](../) एक निर्दिष्ट आकार और शैली का उपयोग करना। वर्ण सेट पर सेट हैDefault , ग्राफिक्स यूनिट कोPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | का एक स्ट्रिंग प्रतिनिधित्व[`Font`](../) नाम। |
| emSize | Single | नए फ़ॉन्ट का एम-आकार, बिंदुओं में। |
| style | FontStyle | [`FontStyle`](../../fontstyle/) नए फ़ॉन्ट का। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या उसके बराबर है, अनंत का मूल्यांकन करता है या मान्य संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### यह सभी देखें

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* नाम स्थान [Aspose.PSD](../../font/)
* सभा [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

एक नया आरंभ करता है[`Font`](../) एक निर्दिष्ट आकार और इकाई का उपयोग करना। वर्ण सेट पर सेट हैDefault शैली पर सेट हैRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | का एक स्ट्रिंग प्रतिनिधित्व[`Font`](../) नाम। |
| emSize | Single | द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का एम-आकार*unit* पैरामीटर। |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) नए फ़ॉन्ट का। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या उसके बराबर है, अनंत का मूल्यांकन करता है या मान्य संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### यह सभी देखें

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* नाम स्थान [Aspose.PSD](../../font/)
* सभा [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

एक नया आरंभ करता है[`Font`](../) एक निर्दिष्ट आकार, शैली, इकाई और वर्ण सेट का उपयोग करना।

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | का एक स्ट्रिंग प्रतिनिधित्व[`Font`](../) नाम। |
| emSize | Single | द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का एम-आकार*unit* पैरामीटर। |
| style | FontStyle | [`FontStyle`](../../fontstyle/) नए फ़ॉन्ट का। |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) नए फ़ॉन्ट का। |
| characterSet | CharacterSet | इस फ़ॉन्ट के लिए उपयोग करने के लिए एक वर्ण सेट। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या उसके बराबर है, अनंत का मूल्यांकन करता है या मान्य संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### यह सभी देखें

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* नाम स्थान [Aspose.PSD](../../font/)
* सभा [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

एक नया आरंभ करता है[`Font`](../) एक निर्दिष्ट आकार, शैली और इकाई का उपयोग करना।

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | का एक स्ट्रिंग प्रतिनिधित्व[`Font`](../) नाम। |
| emSize | Single | द्वारा निर्दिष्ट इकाइयों में नए फ़ॉन्ट का एम-आकार*unit* पैरामीटर। |
| style | FontStyle | [`FontStyle`](../../fontstyle/) नए फ़ॉन्ट का। |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) नए फ़ॉन्ट का। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0 से कम या उसके बराबर है, अनंत का मूल्यांकन करता है या मान्य संख्या नहीं है। |
| ArgumentNullException | *fontName* शून्य है। |

### यह सभी देखें

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* नाम स्थान [Aspose.PSD](../../font/)
* सभा [Aspose.PSD](../../../)


