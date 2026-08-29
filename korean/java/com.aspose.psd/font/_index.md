---
title: "Font"
second_title: "Java용 Aspose.PSD API 참조"
description: "텍스트에 대한 특정 형식을 정의하며, 글꼴 종류, 크기 및 스타일 속성을 포함합니다."
type: docs
weight: 46
url: /ko/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

텍스트에 대한 특정 형식을 정의하며, 글꼴 종류, 크기 및 스타일 속성을 포함합니다. 이 클래스는 상속될 수 없습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | 지정된 기존  com.aspose.psd.Font  및  com.aspose.psd.FontStyle  열거형을 사용하는 새로운  com.aspose.psd.Font  을 초기화합니다. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | 지정된 크기를 사용하여 새로운  com.aspose.psd.Font  을 초기화합니다. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | 지정된 크기와 스타일을 사용하여 새로운  com.aspose.psd.Font  을 초기화합니다. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | 지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운  com.aspose.psd.Font  을 초기화합니다. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | 지정된 크기, 스타일 및 단위를 사용하여 새로운  com.aspose.psd.Font  을 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이  Font  의 정확한 깊은 복사본을 생성합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가  com.aspose.psd.Font  인지 및 이  com.aspose.psd.Font  와 동일한 속성 값을 가지고 있는지 여부를 나타냅니다. |
| [getBold()](#getBold--) | 이  Font  이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다. |
| [getCharacterSet()](#getCharacterSet--) | 이  Font  이 사용하는 문자 집합을 지정하는 바이트 값을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | 이  Font  이 이탤릭인지 여부를 나타내는 값을 가져옵니다. |
| [getName()](#getName--) | 이  Font  의 글꼴 이름을 가져옵니다. |
| [getSize()](#getSize--) | 이  Font  의 em-크기를  P:Aspose.Imaging.Font.Unit  속성에서 지정한 단위로 측정하여 가져옵니다. |
| [getStrikeout()](#getStrikeout--) | 이  Font  이 글꼴에 가로선을 지정하는지 여부를 나타내는 값을 가져옵니다. |
| [getStyle()](#getStyle--) | 이  Font  에 대한 스타일 정보를 가져옵니다. |
| [getUnderline()](#getUnderline--) | 이  Font  이 밑줄이 있는지 여부를 나타내는 값을 가져옵니다. |
| [getUnit()](#getUnit--) | 이  Font  의 측정 단위를 가져옵니다. |
| [hashCode()](#hashCode--) | 이  com.aspose.psd.Font  의 해시 코드를 가져옵니다. |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | 지정된 크기와 단위를 사용하여 새로운  com.aspose.psd.Font  을 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이  com.aspose.psd.Font  의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


지정된 기존  com.aspose.psd.Font  및  com.aspose.psd.FontStyle  열거형을 사용하는 새로운  com.aspose.psd.Font  을 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | 새  com.aspose.psd.Font  를 생성할 기존  com.aspose.psd.Font  입니다. |
| newStyle | int | 새로운  com.aspose.psd.Font 에 적용할  com.aspose.psd.FontStyle입니다. 여러 값의  com.aspose.psd.FontStyle 열거형을 OR 연산자로 결합할 수 있습니다. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


지정된 크기를 사용하여 새로운  com.aspose.psd.Font 를 초기화합니다. 문자 집합은  F:Aspose.Imaging.CharacterSet.Default 로, 그래픽 단위는  F:Aspose.Imaging.GraphicsUnit.Point 로, 글꼴 스타일은  F:Aspose.Imaging.FontStyle.Regular 로 설정됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 이름의 문자열 표현입니다. |
| emSize | float | 새 글꼴의 em-크기(포인트)입니다. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


지정된 크기와 스타일을 사용하여 새로운  com.aspose.psd.Font 를 초기화합니다. 문자 집합은  F:Aspose.Imaging.CharacterSet.Default 로, 그래픽 단위는  F:Aspose.Imaging.GraphicsUnit.Point 로 설정됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 이름의 문자열 표현입니다. |
| emSize | float | 새 글꼴의 em-크기(포인트)입니다. |
| style | int | 새 글꼴의  com.aspose.psd.FontStyle 입니다. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


지정된 크기, 스타일, 단위 및 문자 집합을 사용하여 새로운  com.aspose.psd.Font  을 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 이름의 문자열 표현입니다. |
| emSize | float | unit 매개변수에 지정된 단위로 새 글꼴의 em-크기입니다. |
| style | int | 새 글꼴의  com.aspose.psd.FontStyle 입니다. |
| unit | int | 새 글꼴의  com.aspose.psd.GraphicsUnit 입니다. |
| characterSet | int | 이 글꼴에 사용할 문자 집합입니다. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


지정된 크기, 스타일 및 단위를 사용하여 새로운  com.aspose.psd.Font  을 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 이름의 문자열 표현입니다. |
| emSize | float | unit 매개변수에 지정된 단위로 새 글꼴의 em-크기입니다. |
| style | int | 새 글꼴의  com.aspose.psd.FontStyle 입니다. |
| unit | int | 새 글꼴의  com.aspose.psd.GraphicsUnit 입니다. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


이  Font  의 정확한 깊은 복사본을 생성합니다.

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가  com.aspose.psd.Font  인지 및 이  com.aspose.psd.Font  와 동일한 속성 값을 가지고 있는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체입니다. |

**Returns:**
boolean - obj 매개변수가  com.aspose.psd.Font 이며 이  com.aspose.psd.Font 와 동일한 속성 값을 가지고 있으면 true; 그렇지 않으면 false.
### getBold() {#getBold--}
```
public boolean getBold()
```


이  Font  이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이  Font  이 굵게(bold)이면 true; 그렇지 않으면 false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


이  Font  이 사용하는 문자 집합을 지정하는 바이트 값을 가져옵니다.

**Returns:**
int - 이  Font  이 사용하는 문자 집합입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


이  Font  이 이탤릭인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이  Font  이 이탤릭이면 true; 그렇지 않으면 false.
### getName() {#getName--}
```
public String getName()
```


이  Font  의 글꼴 이름을 가져옵니다.

**Returns:**
java.lang.String - 이  Font  의 얼굴 이름에 대한 문자열 표현입니다.
### getSize() {#getSize--}
```
public float getSize()
```


이  Font  의 em-크기를  P:Aspose.Imaging.Font.Unit  속성에서 지정한 단위로 측정하여 가져옵니다.

**Returns:**
float - 이  Font  의 em-크기입니다.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


이  Font  이 글꼴에 가로선을 지정하는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이  Font  에 가로선이 있으면 true; 그렇지 않으면 false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


이  Font  에 대한 스타일 정보를 가져옵니다.

**Returns:**
int - 이  Font  에 대한 스타일 정보를 포함하는  FontStyle  열거형입니다.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


이  Font  이 밑줄이 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이  Font  에 밑줄이 있으면 true; 그렇지 않으면 false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


이  Font  의 측정 단위를 가져옵니다.

**Returns:**
int - 이  Font  의 측정 단위를 나타내는  GraphicsUnit  입니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이  com.aspose.psd.Font  의 해시 코드를 가져옵니다.

**Returns:**
int - 이  com.aspose.psd.Font  의 해시 코드입니다.
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


지정된 크기와 단위를 사용하여 새로운 com.aspose.psd.Font 를 초기화합니다. 문자 집합은 F:Aspose.Imaging.CharacterSet.Default 로 설정되고, 스타일은 F:Aspose.Imaging.FontStyle.Regular 로 설정됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font 이름의 문자열 표현입니다. |
| emSize | float | unit 매개변수에 지정된 단위로 새 글꼴의 em-크기입니다. |
| unit | int | 새 글꼴의  com.aspose.psd.GraphicsUnit 입니다. |

**Returns:**
[Font](../../com.aspose.psd/font)
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


이  com.aspose.psd.Font  의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 com.aspose.psd.Font 를 나타내는 문자열입니다.
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

