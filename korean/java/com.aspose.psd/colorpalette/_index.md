---
title: "ColorPalette"
second_title: "Java용 Aspose.PSD API 참조"
description: "색상 팔레트를 구성하는 색상 배열을 정의합니다."
type: docs
weight: 27
url: /ko/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

색상 팔레트를 구성하는 색상의 배열을 정의합니다. 색상은 32비트 ARGB 색상입니다. 상속되지 않습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | 새로운 ColorPalette 클래스의 인스턴스를 초기화합니다. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | 새로운 ColorPalette 클래스의 인스턴스를 초기화하고 IsCompactPalette가 false입니다. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | 새로운 ColorPalette 클래스의 인스턴스를 초기화합니다. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | 새로운 ColorPalette 클래스의 인스턴스를 초기화하고 IsCompactPalette가 false입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | 팔레트를 복사합니다. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | 팔레트를 복사합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [getArgb32Entries()](#getArgb32Entries--) | 32-bit ARGB 구조체 배열을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | 인덱스로 팔레트 색상을 가져옵니다. |
| [getEntries()](#getEntries--) | com.aspose.psd.Color 구조체 배열을 가져옵니다. |
| [getEntriesCount()](#getEntriesCount--) | 항목 수를 가져옵니다. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | 컴팩트 팔레트를 사용하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


새로운 ColorPalette 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb32Entries | int[] | 32-bit ARGB 컬러 팔레트 항목입니다. |
| isCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


새로운 ColorPalette 클래스의 인스턴스를 초기화하고 IsCompactPalette가 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb32Entries | int[] | 32-bit ARGB 컬러 팔레트 항목입니다. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


새로운 ColorPalette 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | 색상 팔레트 항목. |
| isCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


새로운 ColorPalette 클래스의 인스턴스를 초기화하고 IsCompactPalette가 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | 색상 팔레트 항목. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


팔레트를 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


팔레트를 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |
| useCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


32-bit ARGB 구조체 배열을 가져옵니다.

**Returns:**
int[] - 항목들. 이 Aspose.Imaging.ColorPalette를 구성하는 32-bit ARGB 구조체 배열입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
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
public Color[] getEntries()
```


com.aspose.psd.Color 구조체 배열을 가져옵니다.

**Returns:**
com.aspose.psd.Color[] - 항목들. 이 Aspose.Imaging.ColorPalette를 구성하는 com.aspose.psd.Color 구조체 배열입니다.
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


항목 수를 가져옵니다.

**Returns:**
int - 항목 수입니다.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


가장 가까운 색상의 인덱스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb32Color | int | 32비트 ARGB 색상. |

**Returns:**
int - 가장 가까운 색상의 인덱스.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


컴팩트 팔레트를 사용하는지 여부를 나타내는 값을 가져오거나 설정합니다.

**Returns:**
boolean - 컴팩트 팔레트를 사용하는 경우 true, 그렇지 않으면 false입니다.

압축 팔레트는 이미지가 가능한 경우 지정된 팔레트 항목만 포함한다는 의미이며, 즉 이미지가 더 작아지고 공간을 덜 차지한다는 뜻입니다; 그렇지 않으면 2^BitsPerPixel 개의 항목이 존재하고 이미지가 모든 가능한 팔레트 항목을 위해 더 많은 공간을 예약합니다. 이 값을 true 로 설정하고 팔레트 항목을 변경하면 데이터 이동이 발생할 수 있어 성능 저하가 발생할 수 있으므로 신중히 사용하십시오.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

