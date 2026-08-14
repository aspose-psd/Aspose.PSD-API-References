---
title: "TiffSRational क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | नया उदाहरण प्रारंभ करता है [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) वर्ग का। |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | नया उदाहरण प्रारंभ करता है [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) वर्ग का। |
| [TiffSRational(value)](#TiffSRational_value_3) | नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| EPSILON [स्थैतिक] | डबल | r | भिन्न गणना के लिए एप्सिलॉन |
| हर | int | r | हर प्राप्त करता है। |
| अंश | int | r | अंश प्राप्त करता है। |
| value | float | r | फ़्लोट मान प्राप्त करता है। |
| value_d | डबल | r | डबल मान प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |
| [approximate_fraction(value)](#approximate_fraction_value_2) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

नया उदाहरण प्रारंभ करता है [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) वर्ग का।

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

नया उदाहरण प्रारंभ करता है [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) वर्ग का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| अंश | int | अंश। |
| हर | int | हर। |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | int | अंश मान। |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | डबल | मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | एक अभाज्य संख्या जिसकी त्रुटि [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) से कम है। |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | float | मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | एक अभाज्य संख्या जिसकी त्रुटि [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) से कम है। |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | डबल | मान। |
| एप्सिलॉन | डबल | अनुमत त्रुटि। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | एक रैशनल संख्या जिसका त्रुटि <paramref name="epsilon" /> से कम है। |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | float | मान। |
| एप्सिलॉन | डबल | अनुमत त्रुटि। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | एक रैशनल संख्या जिसका त्रुटि <paramref name="epsilon" /> से कम है। |


