---
title: "XmpMeta"
second_title: "Java용 Aspose.PSD API 참조"
description: "xmpmeta를 나타냅니다."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

xmpmeta를 나타냅니다. 선택 사항입니다. 이 요소의 목적은 RDF의 다른 비-XMP 사용을 포함할 수 있는 일반 XML 텍스트 내에서 XMP 메타데이터를 식별하는 것입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | XmpMeta 클래스의 새 인스턴스를 초기화합니다. |
| [XmpMeta()](#XmpMeta--) | XmpMeta 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | 속성을 추가합니다. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | 지정된 XMP 요소를 현재 요소에 할당합니다. |
| [clearAttributes()](#clearAttributes--) | 모든 속성을 제거합니다. |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [equals(Object other)](#equals-java.lang.Object-) | 지정된 System.Object가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Adobe Xmp 툴킷 버전을 가져오거나 설정합니다. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | 속성을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | XMP 값을 XML 표현으로 변환합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | 현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | 현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Adobe Xmp 툴킷 버전을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


XmpMeta 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP 툴킷 버전. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


XmpMeta 클래스의 새 인스턴스를 초기화합니다.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


속성을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성. |
| 값 | java.lang.String | 값. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


지정된 XMP 요소를 현재 요소에 할당합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | XMP 요소. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


모든 속성을 제거합니다.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


이 인스턴스를 복제합니다.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


지정된 System.Object가 이 인스턴스와 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 기타 | java.lang.Object | 이 인스턴스와 비교할 System.Object. |

**Returns:**
boolean - 지정된 System.Object가 이 인스턴스와 같으면 true; 그렇지 않으면 false.
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Adobe Xmp 툴킷 버전을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


속성을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성. |

**Returns:**
java.lang.String - 지정된 속성 이름에 대한 속성을 반환합니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP 값을 XML 표현으로 변환합니다.

**Returns:**
java.lang.String - XMP 값을 XML 표현으로 변환한 결과를 반환합니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | 이 객체와 비교할 객체. |

**Returns:**
boolean - 현재 객체가 other 매개변수와 같으면 true; 그렇지 않으면 false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | 이 객체와 비교할 객체. |

**Returns:**
boolean - 현재 객체가 other 매개변수와 같으면 true; 그렇지 않으면 false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Adobe Xmp 툴킷 버전을 가져오거나 설정합니다.

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

