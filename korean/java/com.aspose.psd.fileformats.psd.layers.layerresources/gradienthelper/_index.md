---
title: "GradientHelper"
second_title: "Java용 Aspose.PSD API 참조"
description: "그라디언트 속성에 대한 데이터 변환을 구현하는 도우미 클래스."
type: docs
weight: 34
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

그라디언트 속성에 대한 데이터 변환을 구현하는 도우미 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL 색상 모델 정수 상수 (Noise 그라디언트용). |
| [IntModelLAB](#IntModelLAB) | LBCL 색상 모델 정수 상수 (Noise 그라디언트용). |
| [IntModelRGB](#IntModelRGB) | RGBC 색상 모델 정수 상수 (Noise 그라디언트용). |
| [StrGradientNoise](#StrGradientNoise) | 노이즈 그라디언트 문자열 상수. |
| [StrGradientSolid](#StrGradientSolid) | 솔리드 그라디언트 문자열 상수. |
| [StrModelHSB](#StrModelHSB) | 노이즈 그라디언트를 위한 HSBL 색상 모델 문자열 상수. |
| [StrModelLAB](#StrModelLAB) | 노이즈 그라디언트를 위한 LBCL 색상 모델 문자열 상수. |
| [StrModelRGB](#StrModelRGB) | 노이즈 그라디언트를 위한 RGBC 색상 모델 문자열 상수. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | GradientKind 값을 문자열로 변환합니다. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | 노이즈 색상 모델의 정수 값을 NoiseColorModel로 변환합니다. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | NoiseColorModel 인스턴스를 노이즈 색상 모델의 정수 값으로 변환합니다. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | NoiseColorModel 값을 문자열로 변환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | 문자열 값을 GradientKind로 변환합니다. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | 문자열 값을 NoiseColorModel로 변환합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientHelper() {#GradientHelper--}
```
public GradientHelper()
```


### IntModelHSB {#IntModelHSB}
```
public static final short IntModelHSB
```


HSBL 색상 모델 정수 상수 (Noise 그라디언트용).

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL 색상 모델 정수 상수 (Noise 그라디언트용).

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC 색상 모델 정수 상수 (Noise 그라디언트용).

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


노이즈 그라디언트 문자열 상수.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


솔리드 그라디언트 문자열 상수.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


노이즈 그라디언트를 위한 HSBL 색상 모델 문자열 상수.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


노이즈 그라디언트를 위한 LBCL 색상 모델 문자열 상수.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


노이즈 그라디언트를 위한 RGBC 색상 모델 문자열 상수.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


GradientKind 값을 문자열로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| gradientKind | int | GradientKind 값. |

**Returns:**
java.lang.String - 문자열 값.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToNoiseColorModel(short colorModel) {#intToNoiseColorModel-short-}
```
public static short intToNoiseColorModel(short colorModel)
```


노이즈 색상 모델의 정수 값을 NoiseColorModel로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorModel | short | 노이즈 색상 모델의 정수 값. |

**Returns:**
short - NoiseColorModel 인스턴스.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


NoiseColorModel 인스턴스를 노이즈 색상 모델의 정수 값으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorModel | short | NoiseColorModel 인스턴스. |

**Returns:**
short - Noise 그라디언트 색상 모델의 정수 값.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


NoiseColorModel 값을 문자열로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorModel | short | NoiseColorModel 값. |

**Returns:**
java.lang.String - 색상 모델의 문자열 값.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


문자열 값을 GradientKind로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | java.lang.String | 문자열 값. |

**Returns:**
int - GradientKind 값.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


문자열 값을 NoiseColorModel로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorModel | java.lang.String | 문자열 값. |

**Returns:**
short - NoiseColorModel 값.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

