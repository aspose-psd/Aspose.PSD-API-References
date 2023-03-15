---
title: Color.FromArgb
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Color तरक. एक बनत हैColor 32बट ARGB मन से संरचन.
type: docs
weight: 1430
url: /hi/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

एक बनाता है[`Color`](../) 32-बिट ARGB मान से संरचना.

```csharp
public static Color FromArgb(int argb)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argb | Int32 | 32-बिट ARGB मान निर्दिष्ट करने वाला मान। |

### प्रतिलाभ की मात्रा

[`Color`](../) संरचना जो यह विधि बनाती है।

### यह सभी देखें

* struct [Color](../)
* नाम स्थान [Aspose.PSD](../../color/)
* सभा [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

एक बनाता है[`Color`](../) चार ARGB घटक (अल्फा, लाल, हरा और नीला) मानों से संरचना। हालांकि यह विधि प्रत्येक घटक के लिए 32-बिट मान पारित करने की अनुमति देती है, प्रत्येक घटक का मान 8 बिट तक सीमित है.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alpha | Int32 | अल्फा घटक। मान्य मान 0 से 255 हैं। |
| red | Int32 | लाल घटक। मान्य मान 0 से 255 हैं। |
| green | Int32 | हरा घटक। मान्य मान 0 से 255 हैं। |
| blue | Int32 | नीला घटक। मान्य मान 0 से 255 हैं। |

### प्रतिलाभ की मात्रा

[`Color`](../) कि यह विधि बनाती है।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , या*blue* 0 से कम या 255 से अधिक है। |

### यह सभी देखें

* struct [Color](../)
* नाम स्थान [Aspose.PSD](../../color/)
* सभा [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

एक बनाता है[`Color`](../) निर्दिष्ट से संरचना[`Color`](../) संरचना, लेकिन नए निर्दिष्ट अल्फा मान के साथ। यद्यपि यह विधि 32-बिट मान को अल्फा मान के लिए पारित करने की अनुमति देती है, मान 8 बिट्स तक सीमित है।

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alpha | Int32 | नए के लिए अल्फा मान[`Color`](../). मान्य मान 0 से 255 हैं। |
| baseColor | Color | [`Color`](../) जिससे नया बनाना है[`Color`](../). |

### प्रतिलाभ की मात्रा

[`Color`](../) कि यह विधि बनाती है।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 0 से कम या 255 से अधिक है। |

### यह सभी देखें

* struct [Color](../)
* नाम स्थान [Aspose.PSD](../../color/)
* सभा [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

एक बनाता है[`Color`](../) निर्दिष्ट 8-बिट रंग मानों (लाल, हरा और नीला) से संरचना। अल्फा मान निहित रूप से 255 (पूरी तरह से अपारदर्शी) है। हालांकि यह विधि प्रत्येक रंग घटक के लिए 32-बिट मान पारित करने की अनुमति देती है, प्रत्येक घटक का मान 8 बिट तक सीमित है.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| red | Int32 | नए के लिए लाल घटक मान[`Color`](../). मान्य मान 0 से 255 हैं। |
| green | Int32 | नए के लिए हरा घटक मान[`Color`](../). मान्य मान 0 से 255 हैं। |
| blue | Int32 | नए के लिए नीला घटक मान[`Color`](../). मान्य मान 0 से 255 हैं। |

### प्रतिलाभ की मात्रा

[`Color`](../) कि यह विधि बनाती है।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , या*blue* 0 से कम या 255 से अधिक है। |

### यह सभी देखें

* struct [Color](../)
* नाम स्थान [Aspose.PSD](../../color/)
* सभा [Aspose.PSD](../../../)


