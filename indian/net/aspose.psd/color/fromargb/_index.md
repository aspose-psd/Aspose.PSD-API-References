---
title: "Color.FromArgb"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Color मेथड। 32‑bit ARGB मान से एक Color संरचना बनाता है"
type: docs
weight: 1430
url: /hi/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

एक [`Color`](../) संरचना 32‑bit ARGB मान से बनाता है।

```csharp
public static Color FromArgb(int argb)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| argb | Int32 | 32‑bit ARGB मान को निर्दिष्ट करने वाला मान। |

### रिटर्न वैल्यू

यह मेथड द्वारा निर्मित [`Color`](../) संरचना।

### देखें भी

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

चार ARGB घटकों (alpha, red, green, और blue) मानों से एक [`Color`](../) संरचना बनाता है। हालांकि यह मेथड प्रत्येक घटक के लिए 32‑bit मान पास करने की अनुमति देता है, प्रत्येक घटक का मान 8 बिट तक सीमित है।

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| alpha | Int32 | alpha घटक। मान्य मान 0 से 255 तक हैं। |
| लाल | Int32 | red घटक। मान्य मान 0 से 255 तक हैं। |
| हरा | Int32 | green घटक। मान्य मान 0 से 255 तक हैं। |
| नीला | Int32 | blue घटक। मान्य मान 0 से 255 तक हैं। |

### रिटर्न वैल्यू

यह मेथड द्वारा निर्मित [`Color`](../) है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green*, या *blue* 0 से कम या 255 से अधिक है। |

### देखें भी

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

निर्दिष्ट [`Color`](../) संरचना से एक नया [`Color`](../) संरचना बनाता है, लेकिन नई निर्दिष्ट अल्फा मान के साथ। हालांकि यह विधि अल्फा मान के लिए 32-बिट मान पास करने की अनुमति देती है, मान 8 बिट तक सीमित है।

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| alpha | Int32 | नए [`Color`](../) के लिए अल्फा मान। मान्य मान 0 से 255 तक हैं। |
| baseColor | Color | वह [`Color`](../) जिससे नया [`Color`](../) बनाया जाएगा। |

### रिटर्न वैल्यू

यह मेथड द्वारा निर्मित [`Color`](../) है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 0 से कम या 255 से अधिक है। |

### देखें भी

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

निर्दिष्ट 8-बिट रंग मानों (लाल, हरा, और नीला) से एक [`Color`](../) संरचना बनाता है। अल्फा मान स्वचालित रूप से 255 (पूर्ण अपारदर्शी) होता है। हालांकि यह विधि प्रत्येक रंग घटक के लिए 32-बिट मान पास करने की अनुमति देती है, प्रत्येक घटक का मान 8 बिट तक सीमित है।

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| red | Int32 | नए [`Color`](../) के लाल घटक का मान। मान्य मान 0 से 255 तक हैं। |
| green | Int32 | नए [`Color`](../) के हरे घटक का मान। मान्य मान 0 से 255 तक हैं। |
| blue | Int32 | नए [`Color`](../) के नीले घटक का मान। मान्य मान 0 से 255 तक हैं। |

### रिटर्न वैल्यू

यह मेथड द्वारा निर्मित [`Color`](../) है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green*, या *blue* 0 से कम या 255 से अधिक है। |

### देखें भी

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


