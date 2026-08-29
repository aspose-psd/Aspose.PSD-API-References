---
title: "XmpArray"
second_title: "Java용 Aspose.PSD API 참조"
description: "XmpPackage에서 Xmp Array를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

XmpPackage에서 Xmp Array를 나타냅니다. todo: 배열에 복잡한 데이터가 포함될 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | XmpArray 클래스의 새 인스턴스를 초기화합니다. |
| [XmpArray(int type)](#XmpArray-int-) | XmpArray 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | 새 항목을 추가합니다. |
| [addItem(String item)](#addItem-java.lang.String-) | 새 항목을 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | 내부의 [XmpArray](../../com.aspose.psd.xmp/xmparray) 값 배열을 가져옵니다. |
| [getValues()](#getValues--) | XmpArray 내부의 값 배열을 가져옵니다. |
| [getXmlValue()](#getXmlValue--) | XMP 값을 XML 표현으로 변환합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이 인스턴스를 나타내는  System.String  을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


XmpArray 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 배열의 유형. |
| 항목 | java.lang.String[] | 항목 목록. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


XmpArray 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | int | 배열의 유형. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


새 항목을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 항목 목록에 추가될 요소. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


새 항목을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 항목 | java.lang.String | 항목 목록에 추가될 항목. |

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
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


내부의 [XmpArray](../../com.aspose.psd.xmp/xmparray) 값 배열을 가져옵니다.

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


XmpArray 내부의 값 배열을 가져옵니다.

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP 값을 XML 표현으로 변환합니다.

**Returns:**
java.lang.String - XMP 값을 XML 표현으로 변환한 결과를 반환합니다.
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




### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는  System.String  을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 System.String.
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

