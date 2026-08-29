---
title: "ColorFillSettings"
second_title: "Java용 Aspose.PSD API 참조"
description: "색상 채우기 효과 설정"
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IColorFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/icolorfillsettings)
```
public class ColorFillSettings extends BaseFillSettings implements IColorFillSettings
```

색상 채우기 효과 설정
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorFillSettings()](#ColorFillSettings--) | 새 인스턴스를 초기화합니다 [ColorFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings) 클래스. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 색상을 가져오거나 설정합니다. |
| [getFillType()](#getFillType--) | 채우기 유형 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseEffectResource_internalized(OSTypeStructure structure)](#parseEffectResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 효과 리소스를 구문 분석합니다. |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 값 변경을 발생시킵니다. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 색상을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorFillSettings() {#ColorFillSettings--}
```
public ColorFillSettings()
```


새 인스턴스를 초기화합니다 [ColorFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings) 클래스.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getColor() {#getColor--}
```
public final Color getColor()
```


색상을 가져오거나 설정합니다.

값: 색상.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFillType() {#getFillType--}
```
public int getFillType()
```


채우기 유형

**Returns:**
int
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




### parseEffectResource_internalized(OSTypeStructure structure) {#parseEffectResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void parseEffectResource_internalized(OSTypeStructure structure)
```


효과 리소스를 구문 분석합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 구조. |

### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


값 변경을 발생시킵니다.

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


색상을 가져오거나 설정합니다.

값: 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

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

