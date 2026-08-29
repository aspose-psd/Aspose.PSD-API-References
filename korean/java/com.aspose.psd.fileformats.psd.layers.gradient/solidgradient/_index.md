---
title: "SolidGradient"
second_title: "Java용 Aspose.PSD API 참조"
description: "그라디언트 채우기 효과 설정."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

그라디언트 채우기 효과 설정.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | 새 인스턴스를 초기화합니다 [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | 색상 포인트를 추가합니다. |
| [addTransparencyPoint()](#addTransparencyPoint--) | 색상 포인트를 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | LFX2 리소스 노드를 생성합니다. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | 색상 포인트를 가져오거나 설정합니다. |
| [getGradientMode()](#getGradientMode--) | 이 그라디언트의 모드를 가져옵니다. |
| [getGradientName()](#getGradientName--) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [getInterpolation()](#getInterpolation--) | Interpolation을 가져오거나 설정합니다. |
| [getTransparencyPoints()](#getTransparencyPoints--) | 투명도 포인트를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | 색상 포인트를 제거합니다. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | 투명도 포인트를 제거합니다. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | 색상 포인트를 가져오거나 설정합니다. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolation을 가져오거나 설정합니다. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 투명도 포인트를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


새 인스턴스를 초기화합니다 [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) 클래스.

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


색상 포인트를 추가합니다.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


색상 포인트를 추가합니다.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


LFX2 리소스 노드를 생성합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - 생성된 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 목록
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


색상 포인트를 가져오거나 설정합니다.

값: 색상 포인트.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


이 그라디언트의 모드를 가져옵니다. 'Gradient Type'을 'Solid/Noise'(0/1)으로 결정합니다.

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


그라디언트의 이름을 가져오거나 설정합니다.

값: 그라디언트의 이름.

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolation을 가져오거나 설정합니다. 'Gradient Type' = 'Solid'인 경우 부드러움을 결정합니다. 값 범위: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


투명도 포인트를 가져오거나 설정합니다.

값: 투명도 포인트.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


색상 포인트를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | 포인트. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


투명도 포인트를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | 포인트. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


색상 포인트를 가져오거나 설정합니다.

값: 색상 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


그라디언트의 이름을 가져오거나 설정합니다.

값: 그라디언트의 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolation을 가져오거나 설정합니다. 'Gradient Type' = 'Solid'인 경우 부드러움을 결정합니다. 값 범위: 0-4096.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


투명도 포인트를 가져오거나 설정합니다.

값: 투명도 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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

