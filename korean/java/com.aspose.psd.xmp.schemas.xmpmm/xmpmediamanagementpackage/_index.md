---
title: "XmpMediaManagementPackage"
second_title: "Java용 Aspose.PSD API 참조"
description: "XMP Media Management 네임스페이스를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class XmpMediaManagementPackage extends XmpPackage
```

XMP Media Management 네임스페이스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage--) | XmpMediaManagementPackage 클래스의 새 인스턴스를 초기화합니다. |
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
| [setDerivedFrom(ResourceRef resourceRef)](#setDerivedFrom-com.aspose.psd.xmp.types.complex.resourceref.ResourceRef-) | 파생된 값을 설정합니다. |
| [setDocumentId(String guid)](#setDocumentId-java.lang.String-) | 문서 식별자를 설정합니다. |
| [setDocumentId(UUID guid)](#setDocumentId-java.util.UUID-) | 문서 식별자를 설정합니다. |
| [setDocumentId_internalized(System.Guid guid)](#setDocumentId-internalized-com.aspose.ms.System.Guid-) |  |
| [setInstanceId(String guid)](#setInstanceId-java.lang.String-) | 인스턴스 ID를 설정합니다. |
| [setInstanceId(UUID guid)](#setInstanceId-java.util.UUID-) | 인스턴스 ID를 설정합니다. |
| [setInstanceId_internalized(System.Guid guid)](#setInstanceId-internalized-com.aspose.ms.System.Guid-) |  |
| [setOriginalDocumentId(String guid)](#setOriginalDocumentId-java.lang.String-) | 원본 문서 ID를 설정합니다. |
| [setOriginalDocumentId(UUID guid)](#setOriginalDocumentId-java.util.UUID-) | 원본 문서 ID를 설정합니다. |
| [setOriginalDocumentId_internalized(System.Guid guid)](#setOriginalDocumentId-internalized-com.aspose.ms.System.Guid-) |  |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 값을 설정합니다. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP 부울 값을 설정합니다. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP 고유 식별자를 설정합니다. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP 유형 값을 설정합니다. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 지정된 키로 객체를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMediaManagementPackage() {#XmpMediaManagementPackage--}
```
public XmpMediaManagementPackage()
```


XmpMediaManagementPackage 클래스의 새 인스턴스를 초기화합니다.

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
### setDerivedFrom(ResourceRef resourceRef) {#setDerivedFrom-com.aspose.psd.xmp.types.complex.resourceref.ResourceRef-}
```
public void setDerivedFrom(ResourceRef resourceRef)
```


파생된 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resourceRef | [ResourceRef](../../com.aspose.psd.xmp.types.complex.resourceref/resourceref) | 리소스 참조입니다. |

### setDocumentId(String guid) {#setDocumentId-java.lang.String-}
```
public void setDocumentId(String guid)
```


문서 식별자를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.lang.String | 고유 식별자. |

### setDocumentId(UUID guid) {#setDocumentId-java.util.UUID-}
```
public void setDocumentId(UUID guid)
```


문서 식별자를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.util.UUID | 고유 식별자. |

### setDocumentId_internalized(System.Guid guid) {#setDocumentId-internalized-com.aspose.ms.System.Guid-}
```
public void setDocumentId_internalized(System.Guid guid)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

### setInstanceId(String guid) {#setInstanceId-java.lang.String-}
```
public void setInstanceId(String guid)
```


인스턴스 ID를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.lang.String | 고유 식별자. |

### setInstanceId(UUID guid) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID guid)
```


인스턴스 ID를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.util.UUID | 고유 식별자. |

### setInstanceId_internalized(System.Guid guid) {#setInstanceId-internalized-com.aspose.ms.System.Guid-}
```
public void setInstanceId_internalized(System.Guid guid)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

### setOriginalDocumentId(String guid) {#setOriginalDocumentId-java.lang.String-}
```
public void setOriginalDocumentId(String guid)
```


원본 문서 ID를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.lang.String | 고유 식별자. |

### setOriginalDocumentId(UUID guid) {#setOriginalDocumentId-java.util.UUID-}
```
public void setOriginalDocumentId(UUID guid)
```


원본 문서 ID를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.util.UUID | 고유 식별자. |

### setOriginalDocumentId_internalized(System.Guid guid) {#setOriginalDocumentId-internalized-com.aspose.ms.System.Guid-}
```
public void setOriginalDocumentId_internalized(System.Guid guid)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

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

