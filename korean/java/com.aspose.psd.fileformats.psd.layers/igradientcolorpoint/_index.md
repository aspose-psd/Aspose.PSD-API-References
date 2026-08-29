---
title: "IGradientColorPoint"
second_title: "Java용 Aspose.PSD API 참조"
description: "채우기 설정을 위한 기본 인터페이스"
type: docs
weight: 31
url: /ko/java/com.aspose.psd.fileformats.psd.layers/igradientcolorpoint/
---
```
public interface IGradientColorPoint
```

채우기 설정을 위한 기본 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLocation()](#getLocation--) | 위치를 가져오거나 설정합니다. |
| [getMedianPointLocation()](#getMedianPointLocation--) | 중간점 위치를 가져오거나 설정합니다. |
| [getRawColor()](#getRawColor--) | raw의 색상을 가져오거나 설정합니다. |
| [setLocation(int value)](#setLocation-int-) | 위치를 가져오거나 설정합니다. |
| [setMedianPointLocation(int value)](#setMedianPointLocation-int-) | 중간점 위치를 가져오거나 설정합니다. |
| [setRawColor(RawColor value)](#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | raw의 색상을 가져오거나 설정합니다. |
### getLocation() {#getLocation--}
```
public abstract int getLocation()
```


위치를 가져오거나 설정합니다. 값 범위 0-4096.

값: 위치.

**Returns:**
int
### getMedianPointLocation() {#getMedianPointLocation--}
```
public abstract int getMedianPointLocation()
```


중간점 위치를 가져오거나 설정합니다. 값 범위 0-4096.

값: 중간점 위치.

**Returns:**
int
### getRawColor() {#getRawColor--}
```
public abstract RawColor getRawColor()
```


raw의 색상을 가져오거나 설정합니다.

값: raw의 색상.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### setLocation(int value) {#setLocation-int-}
```
public abstract void setLocation(int value)
```


위치를 가져오거나 설정합니다. 값 범위 0-4096.

값: 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMedianPointLocation(int value) {#setMedianPointLocation-int-}
```
public abstract void setMedianPointLocation(int value)
```


중간점 위치를 가져오거나 설정합니다. 값 범위 0-4096.

값: 중간점 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRawColor(RawColor value) {#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public abstract void setRawColor(RawColor value)
```


raw의 색상을 가져오거나 설정합니다.

값: raw의 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

