---
title: "PsdColorPalette"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 색상 팔레트입니다."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

PSD 색상 팔레트입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다. |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다. |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다. |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다. |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다. |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | 새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | 팔레트를 복사합니다. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | 팔레트를 복사합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | 인덱스로 32비트 ARGB 팔레트 색상을 가져옵니다. |
| [getArgb32Entries()](#getArgb32Entries--) | 32비트 ARGB 색상 배열을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | 인덱스로 팔레트 색상을 가져옵니다. |
| [getEntries()](#getEntries--) | 배열을 가져옵니다 [Color](../../com.aspose.psd/color) 구조체. |
| [getEntriesCount()](#getEntriesCount--) | 항목 수를 가져옵니다. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 가장 가까운 색상의 인덱스를 가져옵니다. |
| [getRawEntries()](#getRawEntries--) | 원시 색상 팔레트 항목 데이터를 가져옵니다. |
| [getRawEntriesCount()](#getRawEntriesCount--) | 원시 색상 팔레트 항목 수를 가져옵니다. |
| [getTransparentColor()](#getTransparentColor--) | 투명 색상을 가져옵니다. |
| [getTransparentIndex()](#getTransparentIndex--) | 투명 색상의 인덱스를 가져옵니다. |
| [hasTransparentColor()](#hasTransparentColor--) | 투명 색상이 존재하는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | 압축된 팔레트인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |
| transparentIndex | short | 투명 색상 인덱스. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rawEntriesData | byte[] | 원시 항목 데이터. |
| isCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rawEntriesData | byte[] | 원시 항목 데이터. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rawEntriesData | byte[] | 원시 항목 데이터. |
| transparentIndex | short | 투명 색상 인덱스. 참고: 이 인덱스는 원시 항목 인덱스가 아니라 변환된 색상 배열을 위한 인덱스입니다. |
| useCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rawEntriesData | byte[] | 원시 항목 데이터. |
| transparentIndex | short | 투명 색상 인덱스. 참고: 이 인덱스는 원시 항목 인덱스가 아니라 변환된 색상 배열을 위한 인덱스입니다. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | 색상 팔레트 32비트 ARGB 항목. |
| isCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 색상 팔레트 항목. |
| isCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 색상 팔레트 항목. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 색상 팔레트 항목. |
| transparentIndex | short | 투명 색상 인덱스. |
| useCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


새로운 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 클래스 인스턴스를 초기화하고 IsCompactPalette는 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 색상 팔레트 항목. |
| transparentIndex | short | 투명 색상 인덱스. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


팔레트를 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


팔레트를 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 색상 팔레트. |
| useCompactPalette | boolean | 압축된 팔레트인지 여부를 나타냅니다. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


32비트 ARGB 색상 배열을 가져옵니다.

**Returns:**
int[] - 이 [ColorPalette](../../com.aspose.psd/colorpalette)를 구성하는 32비트 ARGB 구조체 배열입니다. 값: 항목들.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
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
public final Color[] getEntries()
```


배열을 가져옵니다 [Color](../../com.aspose.psd/color) 구조체.

**Returns:**
com.aspose.psd.Color[] - 이 [Color](../../com.aspose.psd/color) 구조체 배열로, 이 [ColorPalette](../../com.aspose.psd/colorpalette)을 구성합니다. 값: 항목들.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


항목 수를 가져옵니다.

값: 항목 수.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


가장 가까운 색상의 인덱스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb32Color | int | 32비트 ARGB 색상. |

**Returns:**
int - 가장 가까운 색상의 인덱스.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


원시 색상 팔레트 항목 데이터를 가져옵니다.

값: 원시 색상 팔레트 항목 데이터.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


원시 색상 팔레트 항목 수를 가져옵니다.

값: 원시 색상 팔레트 항목 수.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


투명 색상을 가져옵니다.

값: 투명 색상.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


투명 색상의 인덱스를 가져옵니다.

값: 투명 색상의 인덱스.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


투명 색상이 존재하는지 여부를 나타내는 값을 가져옵니다.

값: true 투명 색상이 존재하면; 그렇지 않으면 false.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


압축된 팔레트인지 여부를 나타내는 값을 가져옵니다.

값: true 팔레트를 압축하면; 그렇지 않으면 false.

--------------------

압축 팔레트는 이미지가 가능한 경우 지정된 팔레트 항목만 포함한다는 의미이며, 즉 이미지가 더 작아지고 공간을 덜 차지한다는 뜻입니다; 그렇지 않으면 2^BitsPerPixel 개의 항목이 존재하고 이미지가 모든 가능한 팔레트 항목을 위해 더 많은 공간을 예약합니다. 이 값을 true 로 설정하고 팔레트 항목을 변경하면 데이터 이동이 발생할 수 있어 성능 저하가 발생할 수 있으므로 신중히 사용하십시오.

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

