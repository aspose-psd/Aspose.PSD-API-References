---
title: "GradientColorPoint"
second_title: "Java용 Aspose.PSD API 참조"
description: "그라디언트 색상 포인트."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint)
```
public class GradientColorPoint implements IGradientColorPoint
```

그라디언트 색상 포인트.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GradientColorPoint()](#GradientColorPoint--) | 새로운 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 클래스 인스턴스를 초기화합니다. |
| [GradientColorPoint(Color color, int location, int medianPointLocation)](#GradientColorPoint-com.aspose.psd.Color-int-int-) | 새로운 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(GradientColorPointEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | 색상이 따를 모드 |
| [getLocation()](#getLocation--) | 그라디언트상의 포인트 위치를 가져오거나 설정합니다. |
| [getMedianPointLocation()](#getMedianPointLocation--) | 중간 그라디언트 포인트 위치를 가져오거나 설정합니다. |
| [getRawColor()](#getRawColor--) | raw의 색상을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorMode(short value)](#setColorMode-short-) | 색상이 따를 모드 |
| [setLocation(int value)](#setLocation-int-) | 그라디언트상의 포인트 위치를 가져오거나 설정합니다. |
| [setMedianPointLocation(int value)](#setMedianPointLocation-int-) | 중간 그라디언트 포인트 위치를 가져오거나 설정합니다. |
| [setRawColor(RawColor value)](#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | raw의 색상을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientColorPoint() {#GradientColorPoint--}
```
public GradientColorPoint()
```


새로운 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 클래스 인스턴스를 초기화합니다.

### GradientColorPoint(Color color, int location, int medianPointLocation) {#GradientColorPoint-com.aspose.psd.Color-int-int-}
```
public GradientColorPoint(Color color, int location, int medianPointLocation)
```


새로운 [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 그라디언트상의 색상 포인트. |
| 위치 | int | 그라디언트상의 색상 포인트 위치입니다. |
| 중간점 위치 | int | 중간 그라디언트 포인트 위치입니다. |

### create_internalized(GradientColorPointEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-}
```
public static GradientColorPoint create_internalized(GradientColorPointEntity entity)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity |  |

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint)
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
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


색상이 따를 모드

**Returns:**
short
### getLocation() {#getLocation--}
```
public final int getLocation()
```


그라디언트상의 포인트 위치를 가져오거나 설정합니다.

값: 위치.

**Returns:**
int
### getMedianPointLocation() {#getMedianPointLocation--}
```
public final int getMedianPointLocation()
```


중간 그라디언트 포인트 위치를 가져오거나 설정합니다.

값: 중간점 위치.

**Returns:**
int
### getRawColor() {#getRawColor--}
```
public final RawColor getRawColor()
```


raw의 색상을 가져오거나 설정합니다.

값: raw의 색상.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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




### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


색상이 따를 모드

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setLocation(int value) {#setLocation-int-}
```
public final void setLocation(int value)
```


그라디언트상의 포인트 위치를 가져오거나 설정합니다.

값: 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMedianPointLocation(int value) {#setMedianPointLocation-int-}
```
public final void setMedianPointLocation(int value)
```


중간 그라디언트 포인트 위치를 가져오거나 설정합니다.

값: 중간점 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRawColor(RawColor value) {#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setRawColor(RawColor value)
```


raw의 색상을 가져오거나 설정합니다.

값: raw의 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

