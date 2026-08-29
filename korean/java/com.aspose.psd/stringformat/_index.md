---
title: "StringFormat"
second_title: "Java용 Aspose.PSD API 참조"
description: "정렬 방향 및 탭 정지와 같은 텍스트 레이아웃 정보를 캡슐화하고, 생략 부호 삽입 및 국가별 숫자 대체와 같은 표시 조작 및 OpenType 기능을 포함합니다."
type: docs
weight: 106
url: /ko/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

정렬, 방향 및 탭 정지와 같은 텍스트 레이아웃 정보를 캡슐화하고, 생략 부호 삽입 및 국가별 숫자 대체와 같은 표시 조작 및 OpenType 기능을 제공합니다. 이 클래스는 상속할 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StringFormat()](#StringFormat--) | 새로운  com.aspose.psd.StringFormat  객체를 초기화합니다. |
| [StringFormat(int options)](#StringFormat-int-) | 지정된  com.aspose.psd.StringFormatFlags  열거형 및 언어를 사용하여 새로운  com.aspose.psd.StringFormat  객체를 초기화합니다. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | 지정된 기존  com.aspose.psd.StringFormat  객체에서 새로운  com.aspose.psd.StringFormat  객체를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [deepClone()](#deepClone--) | 이  com.aspose.psd.StringFormat  객체의 깊은 복제본을 생성합니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 수직 평면에서 텍스트 정렬 정보를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | 현지 숫자가 서양 숫자로 대체될 때 사용되는 언어를 가져옵니다. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | 숫자 대체에 사용할 방법을 가져옵니다. |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getFirstTabOffset()](#getFirstTabOffset--) | 텍스트 줄 시작과 첫 번째 탭 정지 사이의 공백 수를 가져옵니다. |
| [getFormatFlags()](#getFormatFlags--) | 서식 정보를 포함하는  com.aspose.psd.StringFormatFlags  열거형을 가져옵니다. |
| [getGenericDefault()](#getGenericDefault--) | 일반 기본  com.aspose.psd.StringFormat  객체를 가져옵니다. |
| [getGenericTypographic()](#getGenericTypographic--) | 일반 타이포그래픽  com.aspose.psd.StringFormat  객체를 가져옵니다. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | 이  com.aspose.psd.StringFormat  객체에 대한  com.aspose.psd.HotkeyPrefix  객체를 가져옵니다. |
| [getLineAlignment()](#getLineAlignment--) | 수평 평면에서 줄 정렬을 가져옵니다. |
| [getTabStops()](#getTabStops--) | 탭 정지 사이의 거리 배열을  P:Aspose.Imaging.getGraphics().PageUnit  속성에서 지정한 단위로 가져옵니다. |
| [getTrimming()](#getTrimming--) | 이 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.StringTrimming 열거형을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | 수직 평면에서 텍스트 정렬 정보를 설정합니다. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | 지역 숫자가 서양 숫자로 대체될 때 사용되는 언어를 설정합니다. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | 숫자 대체에 사용할 방법을 설정합니다. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | 서식 정보를 포함하는 com.aspose.psd.StringFormatFlags 열거형을 설정합니다. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | 이 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.HotkeyPrefix 객체를 설정합니다. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | 수평 평면에서 줄 정렬을 설정합니다. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | 이 com.aspose.psd.StringFormat 객체에 대한 탭 정지를 설정합니다. |
| [setTrimming(int value)](#setTrimming-int-) | 이 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.StringTrimming 열거형을 설정합니다. |
| [toString()](#toString--) | 이 com.aspose.psd.StringFormat 객체를 사람이 읽을 수 있는 문자열로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


새로운  com.aspose.psd.StringFormat  객체를 초기화합니다.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


지정된  com.aspose.psd.StringFormatFlags  열거형 및 언어를 사용하여 새로운  com.aspose.psd.StringFormat  객체를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 옵션 | int | 새 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.StringFormatFlags 열거형입니다. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


지정된 기존  com.aspose.psd.StringFormat  객체에서 새로운  com.aspose.psd.StringFormat  객체를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | 새 com.aspose.psd.StringFormat 객체를 초기화할 com.aspose.psd.StringFormat 객체입니다. |

### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


이  com.aspose.psd.StringFormat  객체의 깊은 복제본을 생성합니다.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


수직 평면에서 텍스트 정렬 정보를 가져옵니다.

**Returns:**
int - 텍스트 정렬 정보를 지정하는 com.aspose.psd.StringAlignment 열거형입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


현지 숫자가 서양 숫자로 대체될 때 사용되는 언어를 가져옵니다.

**Returns:**
int - 지역 숫자가 서양 숫자로 대체될 때 사용될 언어를 식별하는 국가 언어 지원(NLS) 언어 식별자입니다. NLS 언어 식별자로 System.Globalization.CultureInfo 객체의 P:System.Globalization.CultureInfo.LCID 속성을 전달할 수 있습니다. 예를 들어, 문자열 "ar-EG"를 사용하여 System.Globalization.CultureInfo 생성자를 호출해 System.Globalization.CultureInfo 객체를 만든다고 가정합니다. 해당 System.Globalization.CultureInfo 객체의 P:System.Globalization.CultureInfo.LCID 속성과 com.aspose.psd.StringDigitSubstitute.Traditional 를 com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) 메서드에 전달하면, 표시 시에 아라비아-인도 숫자가 서양 숫자로 대체됩니다.

이 설정자는 더 이상 사용되지 않는 메서드 setDigitSubstitution을 위해 도입되었습니다.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


숫자 대체에 사용할 방법을 가져옵니다.

**Returns:**
int - 현재 글꼴에서 지원되지 않아 표시할 수 없는 문자열의 문자를 어떻게 대체할지 지정하는 com.aspose.psd.StringDigitSubstitute 열거형 값입니다.

이 설정자는 더 이상 사용되지 않는 메서드 SetDigitSubstitution을 위해 도입되었습니다.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


텍스트 줄 시작과 첫 번째 탭 정지 사이의 공백 수를 가져옵니다.

**Returns:**
float - 첫 번째 탭 오프셋입니다.

이 속성은 제거된 메서드 GetTabStops를 위해 도입되었습니다.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


서식 정보를 포함하는  com.aspose.psd.StringFormatFlags  열거형을 가져옵니다.

**Returns:**
int - 서식 정보를 포함하는 com.aspose.psd.StringFormatFlags 열거형입니다.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


일반 기본  com.aspose.psd.StringFormat  객체를 가져옵니다.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


일반 타이포그래픽  com.aspose.psd.StringFormat  객체를 가져옵니다.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


이  com.aspose.psd.StringFormat  객체에 대한  com.aspose.psd.HotkeyPrefix  객체를 가져옵니다.

**Returns:**
int - 이 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.HotkeyPrefix 객체이며, 기본값은 F:Aspose.Imaging.HotkeyPrefix.None 입니다.
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


수평 평면에서 줄 정렬을 가져옵니다.

**Returns:**
int - 줄 정렬을 나타내는 com.aspose.psd.StringAlignment 열거형입니다.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


탭 정지 사이의 거리 배열을  P:Aspose.Imaging.getGraphics().PageUnit  속성에서 지정한 단위로 가져옵니다.

**Returns:**
float[] - 탭 정지들입니다.

이 속성은 제거된 메서드 GetTabStops를 위해 도입되었습니다.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


이 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.StringTrimming 열거형을 가져옵니다.

**Returns:**
int - 이 com.aspose.psd.StringFormat 객체로 그린 텍스트가 레이아웃 사각형의 경계를 초과할 때 어떻게 잘리는지를 나타내는 com.aspose.psd.StringTrimming 열거형입니다.
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


수직 평면에서 텍스트 정렬 정보를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 텍스트 정렬 정보를 지정하는  com.aspose.psd.StringAlignment  열거형입니다. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


지역 숫자가 서양 숫자로 대체될 때 사용되는 언어를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 지역 숫자가 서양 숫자로 대체될 때 사용할 언어를 식별하는 국가 언어 지원(NLS) 언어 식별자입니다. NLS 언어 식별자로는  System.Globalization.CultureInfo  객체의  P:System.Globalization.CultureInfo.LCID  속성을 전달할 수 있습니다. 예를 들어, 문자열 "ar-EG"를 사용하여  System.Globalization.CultureInfo  생성자를 호출해 객체를 만든다고 가정합니다. 그 객체의  P:System.Globalization.CultureInfo.LCID  속성을  com.aspose.psd.StringDigitSubstitute.Traditional 와 함께  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)  메서드에 전달하면, 표시 시에 아라비아-인디 숫자가 서양 숫자로 대체됩니다. |

구식 메서드 SetDigitSubstitution에 대해 설정자가 도입되었습니다. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


숫자 대체에 사용할 방법을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 현재 글꼴에서 지원되지 않아 표시할 수 없는 문자열의 문자를 대체하는 방법을 지정하는  com.aspose.psd.StringDigitSubstitute  열거형 값입니다. |

구식 메서드 SetDigitSubstitution에 대해 설정자가 도입되었습니다. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


서식 정보를 포함하는 com.aspose.psd.StringFormatFlags 열거형을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 서식 정보를 포함하는  com.aspose.psd.StringFormatFlags  열거형입니다. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


이 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.HotkeyPrefix 객체를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이  com.aspose.psd.StringFormat  객체에 대한  com.aspose.psd.HotkeyPrefix  객체이며, 기본값은  F:Aspose.Imaging.HotkeyPrefix.None 입니다. |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


수평 평면에서 줄 정렬을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 줄 정렬을 나타내는  com.aspose.psd.StringAlignment  열거형입니다. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


이 com.aspose.psd.StringFormat 객체에 대한 탭 정지를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| firstTabOffset | float | 텍스트 줄 시작과 첫 번째 탭 정지점 사이의 공백 수입니다. |
| tabStops | float[] | 탭 정지점 사이의 거리를  com.aspose.psd.Graphics.PageUnit  속성에서 지정한 단위로 나타낸 배열입니다. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


이 com.aspose.psd.StringFormat 객체에 대한 com.aspose.psd.StringTrimming 열거형을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이  com.aspose.psd.StringFormat  객체로 그린 텍스트가 레이아웃 사각형의 경계를 초과할 때 어떻게 잘릴지를 나타내는  com.aspose.psd.StringTrimming  열거형입니다. |

### toString() {#toString--}
```
public String toString()
```


이 com.aspose.psd.StringFormat 객체를 사람이 읽을 수 있는 문자열로 변환합니다.

**Returns:**
java.lang.String - 이  com.aspose.psd.StringFormat  객체의 문자열 표현입니다.
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

