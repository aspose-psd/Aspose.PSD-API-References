---
title: "IColorPalette"
second_title: "Java용 Aspose.PSD API 참조"
description: "컬러 팔레트 인터페이스입니다."
type: docs
weight: 117
url: /ko/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

컬러 팔레트 인터페이스입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [getArgb32Entries()](#getArgb32Entries--) | 32-bit ARGB 구조체 배열을 가져옵니다. |
| [getColor(int index)](#getColor-int-) | 인덱스로 팔레트 색상을 가져옵니다. |
| [getEntries()](#getEntries--) | com.aspose.psd.Color 구조체 배열을 가져옵니다. |
| [getEntriesCount()](#getEntriesCount--) | 항목 수를 가져옵니다. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 가장 가까운 32비트 ARGB 색상의 인덱스를 가져옵니다. |
| [isCompactPalette()](#isCompactPalette--) | 컴팩트 팔레트가 사용되는지 여부를 나타내는 값을 가져옵니다. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
```


인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 32비트 ARGB 팔레트 색상 인덱스. |

**Returns:**
int - 지정된 인덱스에 의해 지정된 색상 팔레트 항목.
### getArgb32Entries() {#getArgb32Entries--}
```
public abstract int[] getArgb32Entries()
```


32-bit ARGB 구조체 배열을 가져옵니다.

**Returns:**
int[] - 32비트 ARGB 항목입니다. 이 com.aspose.psd.ColorPalette 를 구성하는 32비트 ARGB 구조체 배열입니다.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
```


인덱스로 팔레트 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 팔레트 색상 인덱스. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public abstract Color[] getEntries()
```


com.aspose.psd.Color 구조체 배열을 가져옵니다.

**Returns:**
com.aspose.psd.Color[] - 항목들입니다. 이 com.aspose.psd.ColorPalette 를 구성하는 com.aspose.psd.Color 구조체 배열입니다.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


항목 수를 가져옵니다.

**Returns:**
int - 항목 수입니다.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
```


가장 가까운 색상의 인덱스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 색상. |

**Returns:**
int - 가장 가까운 색상의 인덱스.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public abstract int getNearestColorIndex(int argb32Color)
```


가장 가까운 32비트 ARGB 색상의 인덱스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb32Color | int | 32비트 ARGB 색상. |

**Returns:**
int - 가장 가까운 색상의 인덱스.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


컴팩트 팔레트가 사용되는지 여부를 나타내는 값을 가져옵니다.

압축 팔레트는 이미지가 가능한 경우 지정된 팔레트 항목만 포함한다는 의미이며, 즉 이미지가 더 작아지고 공간을 덜 차지한다는 뜻입니다; 그렇지 않으면 2^BitsPerPixel 개의 항목이 존재하고 이미지가 모든 가능한 팔레트 항목을 위해 더 많은 공간을 예약합니다. 이 값을 true 로 설정하고 팔레트 항목을 변경하면 데이터 이동이 발생할 수 있어 성능 저하가 발생할 수 있으므로 신중히 사용하십시오.

**Returns:**
boolean - 컴팩트 팔레트를 사용하는 경우 true, 그렇지 않으면 false입니다.
