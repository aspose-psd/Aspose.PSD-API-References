---
title: "TiffRational क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का। |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का। |
| [TiffRational(value)](#TiffRational_value_3) | नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| EPSILON [स्थैतिक] | डबल | r | भिन्न गणना के लिए एप्सिलॉन |
| हर | uint | r | हर प्राप्त करता है। |
| अंश | uint | r | अंश प्राप्त करता है। |
| value | float | r | फ़्लोट मान प्राप्त करता है। |
| value_d | डबल | r | डबल मान प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |
| [approximate_fraction(value)](#approximate_fraction_value_2) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | प्रदान किए गए मान को एक भिन्न में निकटतम बनाता है। |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का।

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| अंश | uint | अंश। |
| हर | uint | हर। |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

नए उदाहरण को प्रारंभ करता है [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | uint | अंश मान। |

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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | एक रैशनल संख्या जिसका त्रुटि [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) से कम है। |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | एक रैशनल संख्या जिसका त्रुटि [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) से कम है। |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | एक रैशनल संख्या जिसका त्रुटि <paramref name="epsilon" /> से कम है। |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | एक रैशनल संख्या जिसका त्रुटि <paramref name="epsilon" /> से कम है। |


