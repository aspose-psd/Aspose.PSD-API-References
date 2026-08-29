---
title: "PhotoshopPackage"
second_title: "Java용 Aspose.PSD API 참조"
description: "Adobe Photoshop 네임스페이스를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Adobe Photoshop 네임스페이스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | PhotoshopPackage 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | 긴급도 최대값. |
| [UrgencyMin](#UrgencyMin) | 긴급도 최소값. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | 복합 유형 네임스페이스를 추가합니다. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | 문자열 속성을 추가합니다. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | 지정된 XMP 패키지를 현재 패키지에 할당합니다. |
| [clear()](#clear--) | 이 인스턴스를 초기화합니다. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | 패키지를 결합합니다. |
| [containsKey(String key)](#containsKey-java.lang.String-) | 지정된 키가 키를 포함하는지 확인합니다. |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | XMP 패키지의 키를 가져옵니다. |
| [getNamespaceUri()](#getNamespaceUri--) | 네임스페이스 URI를 가져옵니다. |
| [getPrefix()](#getPrefix--) | 접두사를 가져옵니다. |
| [getXmlNamespace()](#getXmlNamespace--) | XML 네임스페이스를 가져옵니다. |
| [getXmlValue()](#getXmlValue--) | XMP 값을 XML 표현으로 변환합니다. |
| [get_Item(String key)](#get-Item-java.lang.String-) | 지정된 키와 함께 Object를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | 지정된 키와 함께 값을 제거합니다. |
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | 작성자 위치를 설정합니다. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | 캡션 작성자를 설정합니다. |
| [setCategory(String category)](#setCategory-java.lang.String-) | 카테고리를 설정합니다. |
| [setCity(String city)](#setCity-java.lang.String-) | 도시를 설정합니다. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | 색상 모드를 설정합니다. |
| [setCountry(String country)](#setCountry-java.lang.String-) | 국가를 설정합니다. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | 생성 날짜를 설정합니다. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | 크레딧을 설정합니다. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | 문서 조상을 설정합니다. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | 헤드라인을 설정합니다. |
| [setHistory(String history)](#setHistory-java.lang.String-) | 히스토리를 설정합니다. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | ICC 프로파일을 설정합니다. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | 지침을 설정합니다. |
| [setSource(String source)](#setSource-java.lang.String-) | 소스를 설정합니다. |
| [setState(String state)](#setState-java.lang.String-) | 상태를 설정합니다. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | 보조 카테고리를 설정합니다. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | 전송 참조를 설정합니다. |
| [setUrgency(int urgency)](#setUrgency-int-) | 긴급성을 설정합니다. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 값을 설정합니다. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP 부울 값을 설정합니다. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP 고유 식별자를 설정합니다. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP 유형 값을 설정합니다. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 지정된 키로 객체를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


PhotoshopPackage 클래스의 새 인스턴스를 초기화합니다.

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


긴급도 최대값.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


긴급도 최소값.

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


복합 유형 네임스페이스를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typePrefix | java.lang.String | 유형 접두사. |
| typeNamespaceUri | java.lang.String | 유형 네임스페이스 URI. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


문자열 속성을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 추가된 값과 식별되는 키의 문자열 표현. |
| 값 | java.lang.String | 문자열 값. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


지정된 XMP 패키지를 현재 패키지에 할당합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | XMP 패키지. |

### clear() {#clear--}
```
public void clear()
```


이 인스턴스를 초기화합니다.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


패키지를 결합합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 결합할 다른 패키지. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


지정된 키가 키를 포함하는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 확인할 키. |

**Returns:**
boolean - 지정된 키에 키가 포함되어 있으면 true를 반환합니다.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


이 인스턴스를 복제합니다.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


XMP 패키지의 키를 가져옵니다.

값: XMP 패키지의 키들.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


네임스페이스 URI를 가져옵니다.

값: 네임스페이스 URI.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


접두사를 가져옵니다.

값: 접두사.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


XML 네임스페이스를 가져옵니다.

값: XML 네임스페이스.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP 값을 XML 표현으로 변환합니다.

**Returns:**
java.lang.String - XMP 값을 XML 표현으로 변환한 결과를 반환합니다.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


지정된 키와 함께 Object를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 값을 식별하는 키. |

**Returns:**
java.lang.Object - 지정된 키와 함께하는  Object  를 반환합니다.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


컬렉션을 반복하는 열거자를 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - 컬렉션을 반복하는 데 사용할 수 있는  T:System.Collections.Generic.IEnumerator1  입니다.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


지정된 키와 함께 값을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 제거된 값과 식별된 키의 문자열 표현. |

**Returns:**
boolean - 지정된 키의 값이 제거된 경우 true를 반환합니다.
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


작성자 위치를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| authorsPosition | java.lang.String | 저자 위치. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


캡션 작성자를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| captionWriter | java.lang.String | 캡션 작성기. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


카테고리를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| category | java.lang.String | 카테고리. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


도시를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| city | java.lang.String | 도시 이름. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


색상 모드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorMode | byte | 색상 모드. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


국가를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| country | java.lang.String | 국가. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


생성 날짜를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| createdDate | java.util.Date | 생성 날짜. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


크레딧을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 크레딧 | java.lang.String | 크레딧. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


문서 조상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 조상들 | java.lang.String[] | 조상들. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


헤드라인을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 헤드라인 | java.lang.String | 헤드라인. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


히스토리를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 기록 | java.lang.String | 기록. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


ICC 프로파일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| iccProfile | java.lang.String | icc 프로필. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


지침을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 지침 | java.lang.String | 지침. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


소스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 소스 | java.lang.String | 소스. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


상태를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 상태 | java.lang.String | 상태. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


보조 카테고리를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | 보조 카테고리. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


전송 참조를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| transmissionReference | java.lang.String | 전송 참조. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


긴급성을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 긴급도 | int | 긴급도. |

긴급도는 1에서 8 사이여야 합니다. |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 추가된 값과 식별되는 키의 문자열 표현. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | 추가할 값. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


XMP 부울 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 설정된 값으로 식별되는 키의 문자열 표현입니다. |
| boolValue | java.lang.String | 불리언 값. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


XMP 고유 식별자를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 설정된 GUID 값으로 식별되는 키의 문자열 표현. |
| guid | java.lang.String | 고유 식별자. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


XMP 유형 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 설정된 값으로 식별되는 키의 문자열 표현입니다. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | 설정할 값. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


지정된 키로 객체를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 값을 식별하는 키. |
| 값 | java.lang.Object | 객체 값. |

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

