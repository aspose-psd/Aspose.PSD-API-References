---
title: "Font"
second_title: "Java용 Aspose.PSD API 참조"
description: "XMP Font을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

XMP Font을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Font()](#Font--) | Font 클래스의 새 인스턴스를 초기화합니다. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Font 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 지정된 키를 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | 복합 글꼴을 구성하는 글꼴의 파일 이름 배열을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | 글꼴 모양을 가져오거나 설정합니다. |
| [getFontFamily()](#getFontFamily--) | 글꼴 패밀리를 가져오거나 설정합니다. |
| [getFontFileName()](#getFontFileName--) | 전체 경로 없이 글꼴 파일 이름을 가져오거나 설정합니다. |
| [getFontName()](#getFontName--) | PostScript 글꼴 이름을 가져오거나 설정합니다. |
| [getFontType()](#getFontType--) | 글꼴 유형을 가져오거나 설정합니다. |
| [getNamespaceUri()](#getNamespaceUri--) | 기본 네임스페이스 URI를 가져옵니다. |
| [getPrefix()](#getPrefix--) | 접두사를 가져옵니다. |
| [getVersion()](#getVersion--) | 글꼴 버전을 가져오거나 설정합니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식의 문자열 포함 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | 이 글꼴이 복합인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | 복합 글꼴을 구성하는 글꼴의 파일 이름 배열을 가져오거나 설정합니다. |
| [setComposite(boolean value)](#setComposite-boolean-) | 이 글꼴이 복합인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | 글꼴 모양을 가져오거나 설정합니다. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | 글꼴 패밀리를 가져오거나 설정합니다. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | 전체 경로 없이 글꼴 파일 이름을 가져오거나 설정합니다. |
| [setFontName(String value)](#setFontName-java.lang.String-) | PostScript 글꼴 이름을 가져오거나 설정합니다. |
| [setFontType(String value)](#setFontType-java.lang.String-) | 글꼴 유형을 가져오거나 설정합니다. |
| [setVersion(String value)](#setVersion-java.lang.String-) | 글꼴 버전을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Font 클래스의 새 인스턴스를 초기화합니다.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Font 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontFamily | java.lang.String | 폰트 패밀리. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


지정된 키를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 추가된 값과 식별되는 키의 문자열 표현. |
| 값 | java.lang.Object | 추가할 값. |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


복합 글꼴을 구성하는 글꼴의 파일 이름 배열을 가져오거나 설정합니다.

Value: 복합 폰트를 구성하는 폰트 파일 이름들의 배열.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


글꼴 모양을 가져오거나 설정합니다.

Value: 폰트 페이스.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


글꼴 패밀리를 가져오거나 설정합니다.

Value: 폰트 패밀리.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


전체 경로 없이 글꼴 파일 이름을 가져오거나 설정합니다.

Value: 전체 경로 없이 폰트 파일 이름.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


PostScript 글꼴 이름을 가져오거나 설정합니다.

Value: PostScript 폰트 이름.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


글꼴 유형을 가져오거나 설정합니다.

TrueType, Type 1, Open Type 등. Value: 폰트 유형.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


기본 네임스페이스 URI를 가져옵니다.

**Returns:**
java.lang.String - 기본 네임스페이스 URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


접두사를 가져옵니다.

**Returns:**
java.lang.String - 접두사.
### getVersion() {#getVersion--}
```
public String getVersion()
```


글꼴 버전을 가져오거나 설정합니다.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts 비트맵 폰트의 경우 빈 문자열 Value: 폰트 버전.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 형식의 문자열 포함 값을 가져옵니다.

**Returns:**
java.lang.String - XMP 형식의 문자열 포함 값을 반환합니다.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


이 글꼴이 복합인지 여부를 나타내는 값을 가져오거나 설정합니다.

Value:  true  이 폰트가 복합 폰트인 경우; 그렇지 않으면  false .

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




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


복합 글꼴을 구성하는 글꼴의 파일 이름 배열을 가져오거나 설정합니다.

Value: 복합 폰트를 구성하는 폰트 파일 이름들의 배열.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


이 글꼴이 복합인지 여부를 나타내는 값을 가져오거나 설정합니다.

Value:  true  이 폰트가 복합 폰트인 경우; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


글꼴 모양을 가져오거나 설정합니다.

Value: 폰트 페이스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


글꼴 패밀리를 가져오거나 설정합니다.

Value: 폰트 패밀리.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


전체 경로 없이 글꼴 파일 이름을 가져오거나 설정합니다.

Value: 전체 경로 없이 폰트 파일 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


PostScript 글꼴 이름을 가져오거나 설정합니다.

Value: PostScript 폰트 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


글꼴 유형을 가져오거나 설정합니다.

TrueType, Type 1, Open Type 등. Value: 폰트 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


글꼴 버전을 가져오거나 설정합니다.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts 비트맵 폰트의 경우 빈 문자열 Value: 폰트 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

