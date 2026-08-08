---
title: "RdOptimizerSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "RD 옵티마이저 설정 클래스."
type: docs
weight: 22
url: /ko/java/com.aspose.psd.imageoptions/rdoptimizersettings/
---

**Inheritance:**
java.lang.Object
```
public class RdOptimizerSettings
```

RD 옵티마이저 설정 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RdOptimizerSettings()](#RdOptimizerSettings--) | RdOptimizerSettings 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create()](#create--) | 이 인스턴스를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBppMax()](#getBppMax--) | 비트당 픽셀에서 고려되는 최대 R 값을 가져옵니다. |
| [getBppScale()](#getBppScale--) | BPP(비트당 픽셀) 스케일 팩터를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDcClamp_internalized()](#getDcClamp-internalized--) | 블록의 첫 번째 왼쪽 위 픽셀에 대한 양자화 값 범위를 제한하기 위한 DC 클램프 값을 가져옵니다. |
| [getDiscretizedBppMax()](#getDiscretizedBppMax--) | 고려되는 최대 R 값을 가져옵니다. |
| [getMaxChannel_internalized()](#getMaxChannel-internalized--) | 사용할 최대 색 채널 수를 가져옵니다. |
| [getMaxPixelValue()](#getMaxPixelValue--) | 최대 픽셀 값을 가져옵니다. |
| [getMaxQ()](#getMaxQ--) | 최대 양자화 값을 가져옵니다. |
| [getMinQ()](#getMinQ--) | 허용되는 최소 양자화 값을 가져옵니다. |
| [getPsnrMax()](#getPsnrMax--) | PSNR 최대 예상 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBppMax(double value)](#setBppMax-double-) | 비트당 픽셀에서 고려되는 최대 R 값을 설정합니다. |
| [setBppScale(int value)](#setBppScale-int-) | BPP(비트당 픽셀) 스케일 팩터를 설정합니다. |
| [setMaxChannel_internalized(int value)](#setMaxChannel-internalized-int-) | 사용할 최대 색 채널 수를 설정합니다. |
| [setMaxQ(int value)](#setMaxQ-int-) | 최대 양자화 값을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RdOptimizerSettings() {#RdOptimizerSettings--}
```
public RdOptimizerSettings()
```


RdOptimizerSettings 클래스의 새 인스턴스를 초기화합니다.

### create() {#create--}
```
public static RdOptimizerSettings create()
```


이 인스턴스를 생성합니다.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - returns RDOptimizerSettings class instance
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
### getBppMax() {#getBppMax--}
```
public double getBppMax()
```


비트당 픽셀에서 고려되는 최대 R 값을 가져옵니다.

**Returns:**
double - 비트당 픽셀에서 고려되는 최대 R 값.
### getBppScale() {#getBppScale--}
```
public int getBppScale()
```


BPP(비트당 픽셀) 스케일 팩터를 가져옵니다.

**Returns:**
int - BPP 스케일.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDcClamp_internalized() {#getDcClamp-internalized--}
```
public int getDcClamp_internalized()
```


블록의 첫 번째 왼쪽 위 픽셀에 대한 양자화 값 범위를 제한하기 위한 DC 클램프 값을 가져옵니다.

**Returns:**
int - DC 클램프 값.
### getDiscretizedBppMax() {#getDiscretizedBppMax--}
```
public int getDiscretizedBppMax()
```


고려되는 최대 R 값을 가져옵니다.

**Returns:**
int - 고려 대상인 최대 R 값.
### getMaxChannel_internalized() {#getMaxChannel-internalized--}
```
public int getMaxChannel_internalized()
```


사용할 최대 색 채널 수를 가져옵니다.

**Returns:**
int - 최대 색 채널 인덱스.
### getMaxPixelValue() {#getMaxPixelValue--}
```
public int getMaxPixelValue()
```


최대 픽셀 값을 가져옵니다.

**Returns:**
int - 최대 최대 픽셀 값.
### getMaxQ() {#getMaxQ--}
```
public int getMaxQ()
```


최대 양자화 값을 가져옵니다.

**Returns:**
int - 최대 양자화 값.
### getMinQ() {#getMinQ--}
```
public int getMinQ()
```


허용되는 최소 양자화 값을 가져옵니다.

**Returns:**
int - 허용되는 최소 최소 양자화 값.
### getPsnrMax() {#getPsnrMax--}
```
public int getPsnrMax()
```


PSNR 최대 예상 값을 가져옵니다.

**Returns:**
int - 최대 최대 픽셀 값.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBppMax(double value) {#setBppMax-double-}
```
public void setBppMax(double value)
```


비트당 픽셀에서 고려되는 최대 R 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 비트당 픽셀에서 고려되는 최대 R 값. |

### setBppScale(int value) {#setBppScale-int-}
```
public void setBppScale(int value)
```


BPP(비트당 픽셀) 스케일 팩터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | BPP 스케일. |

### setMaxChannel_internalized(int value) {#setMaxChannel-internalized-int-}
```
public void setMaxChannel_internalized(int value)
```


사용할 최대 색 채널 수를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 최대 색 채널 인덱스. |

### setMaxQ(int value) {#setMaxQ-int-}
```
public void setMaxQ(int value)
```


최대 양자화 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 최대 양자화 값. |

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

