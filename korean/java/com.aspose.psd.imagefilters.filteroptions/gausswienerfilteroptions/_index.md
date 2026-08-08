---
title: "GaussWienerFilterOptions"
second_title: "Java용 Aspose.PSD API 참조"
description: "Gauss Wiener 필터 옵션 디블러 가우스"
type: docs
weight: 15
url: /ko/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Gauss Wiener 필터 옵션 디블러 가우스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | GaussWienerFilterOptions 클래스의 새 인스턴스를 초기화합니다. |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | GaussWienerFilterOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | brightness를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | 이 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)가 그레이스케일인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getRadius()](#getRadius--) | 반경을 가져오거나 설정합니다. |
| [getSmooth()](#getSmooth--) | 부드러움을 가져오거나 설정합니다. |
| [getSnr()](#getSnr--) | SNR(신호 대 잡음 비율)를 가져오거나 설정합니다. 권장 범위 0.002 - 0.009, 기본값 = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | 이 인스턴스가 부분적으로 로드되었는지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | brightness를 가져오거나 설정합니다. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | 이 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)가 그레이스케일인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | 이 인스턴스가 부분적으로 로드되었는지 여부를 나타내는 값을 가져옵니다. |
| [setRadius(int value)](#setRadius-int-) | 반경을 가져오거나 설정합니다. |
| [setSmooth(double value)](#setSmooth-double-) | 부드러움을 가져오거나 설정합니다. |
| [setSnr(double value)](#setSnr-double-) | SNR(신호 대 잡음 비율)를 가져오거나 설정합니다. 권장 범위 0.002 - 0.009, 기본값 = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


GaussWienerFilterOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 반경 | int | 반경. |
| 부드러움 | double | 부드러움. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


GaussWienerFilterOptions 클래스의 새 인스턴스를 초기화합니다. 기본 설정으로.

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
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


밝기를 가져오거나 설정합니다. 권장 범위 1 - 1.5, 기본값 = 1.15

값: brightness.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


이 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)가 그레이스케일인지 여부를 나타내는 값을 가져오거나 설정합니다. 그레이스케일 모드 또는 RGB 모드를 반환합니다.

값:  true  그레이스케일인 경우; 그렇지 않으면  false .

**Returns:**
boolean
### getRadius() {#getRadius--}
```
public int getRadius()
```


반경을 가져오거나 설정합니다.

값: 반경.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


부드러움을 가져오거나 설정합니다.

값: 부드러움.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


SNR(신호 대 잡음 비율)를 가져오거나 설정합니다. 권장 범위 0.002 - 0.009, 기본값 = 0.007

값: SNR.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


이 인스턴스가 부분적으로 로드되었는지 여부를 나타내는 값을 가져옵니다.

값:  true  이 인스턴스가 부분적으로 로드된 경우; 그렇지 않으면  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


밝기를 가져오거나 설정합니다. 권장 범위 1 - 1.5, 기본값 = 1.15

값: brightness.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


이 [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)가 그레이스케일인지 여부를 나타내는 값을 가져오거나 설정합니다. 그레이스케일 모드 또는 RGB 모드를 반환합니다.

값:  true  그레이스케일인 경우; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


이 인스턴스가 부분적으로 로드되었는지 여부를 나타내는 값을 가져옵니다.

값:  true  이 인스턴스가 부분적으로 로드된 경우; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


반경을 가져오거나 설정합니다.

값: 반경.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


부드러움을 가져오거나 설정합니다.

값: 부드러움.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


SNR(신호 대 잡음 비율)를 가져오거나 설정합니다. 권장 범위 0.002 - 0.009, 기본값 = 0.007

값: SNR.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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

