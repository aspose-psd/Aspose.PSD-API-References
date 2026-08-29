---
title: "XmpBasicPackage"
second_title: "Java용 Aspose.PSD API 참조"
description: "XMP 기본 네임스페이스를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

XMP 기본 네임스페이스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | XmpBasicPackage 클래스의 새 인스턴스를 초기화합니다. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | XmpBasicPackage 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [RatingMax](#RatingMax) | 평점 최대값. |
| [RatingMin](#RatingMin) | 평점 최소값. |
| [RatingRejected](#RatingRejected) | 평점 거부값. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | 지정된 키를 가진 객체를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | 지정된 키와 함께 값을 제거합니다. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | 리소스 생성 날짜를 추가합니다. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | 리소스 생성 날짜를 추가합니다. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | 생성자 도구를 설정합니다. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | 식별자를 설정합니다. |
| [setLabel(String label)](#setLabel-java.lang.String-) | 레이블을 설정합니다. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | 메타데이터 마지막 변경 날짜를 추가합니다. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | 메타데이터 마지막 변경 날짜를 추가합니다. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | 리소스 마지막 수정 날짜를 추가합니다. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | 리소스 마지막 수정 날짜를 추가합니다. |
| [setRating(int choise)](#setRating-int-) | 평점을 설정합니다. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 값을 설정합니다. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP 부울 값을 설정합니다. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP 고유 식별자를 설정합니다. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP 유형 값을 설정합니다. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 지정된 키를 가진 객체를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


XmpBasicPackage 클래스의 새 인스턴스를 초기화합니다.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


XmpBasicPackage 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | java.lang.String | 접두사입니다. |
| namespaceUri | java.lang.String | 네임스페이스 URI입니다. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


평점 최대값.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


평점 최소값.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


평점 거부값.

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


지정된 키를 가진 객체를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 값을 식별하는 키입니다. 값: 객체. |

**Returns:**
java.lang.Object - 지정된 키와 함께 객체를 반환합니다.
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


리소스 생성 날짜를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| createdDate | java.lang.String | 생성 날짜. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


리소스 생성 날짜를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | 생성 날짜. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


생성자 도구를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| creatorTool | java.lang.String | 도구 이름. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


식별자를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 식별자 | java.lang.String[] | 식별자입니다. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


레이블을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 레이블 | java.lang.String | 레이블입니다. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


메타데이터 마지막 변경 날짜를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| metadataDate | java.lang.String | 메타데이터 날짜. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


메타데이터 마지막 변경 날짜를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | 메타데이터 날짜. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


리소스 마지막 수정 날짜를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| modifiedDate | java.lang.String | 마지막 수정 날짜. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


리소스 마지막 수정 날짜를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | 마지막 수정 날짜. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


평점을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 선택 | int | -1부터 5까지 |

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


지정된 키를 가진 객체를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 값을 식별하는 키입니다. 값: 객체. |
| 값 | java.lang.Object |  |

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

