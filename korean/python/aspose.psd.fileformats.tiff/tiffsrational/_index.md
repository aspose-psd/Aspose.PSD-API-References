---
title: "TiffSRational 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | 새 인스턴스를 초기화합니다 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 클래스. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | 새 인스턴스를 초기화합니다 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 클래스. |
| [TiffSRational(value)](#TiffSRational_value_3) | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | 분수 계산을 위한 epsilon |
| 분모 | int | r | 분모를 가져옵니다. |
| 분자 | int | r | 분자를 가져옵니다. |
| 값 | float | r | float 값을 가져옵니다. |
| value_d | double | r | double 값을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | 제공된 값을 분수로 근사합니다. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | 제공된 값을 분수로 근사합니다. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | 제공된 값을 분수로 근사합니다. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | 제공된 값을 분수로 근사합니다. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

새 인스턴스를 초기화합니다 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 클래스.

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

새 인스턴스를 초기화합니다 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 분자 | int | 분자. |
| 분모 | int | 분모. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

[TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | int | 분자 값. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

제공된 값을 분수로 근사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | double | 값입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 오차가 [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/)보다 작은 유리수. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

제공된 값을 분수로 근사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | float | 값입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 오차가 [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/)보다 작은 유리수. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

제공된 값을 분수로 근사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | double | 값입니다. |
| epsilon | double | 허용되는 오류. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 오차가 <paramref name="epsilon" />보다 작은 유리수. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

제공된 값을 분수로 근사합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 값 | float | 값입니다. |
| epsilon | double | 허용되는 오류. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 오차가 <paramref name="epsilon" />보다 작은 유리수. |


