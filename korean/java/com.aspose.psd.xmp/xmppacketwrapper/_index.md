---
title: "XmpPacketWrapper"
second_title: "Java용 Aspose.PSD API 참조"
description: "헤더와 트레일러를 포함한 직렬화된 xmp 패키지를 포함합니다."
type: docs
weight: 20
url: /ko/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

헤더와 트레일러를 포함한 직렬화된 xmp 패키지를 포함합니다.

XML 처리 명령(PIs) 한 쌍으로 구성된 래퍼가 rdf:RDF 요소 주위에 배치될 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | 새로운  XmpPacketWrapper  클래스 인스턴스를 초기화합니다. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | 새로운  XmpPacketWrapper  클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | 패키지를 추가합니다. |
| [clearPackages()](#clearPackages--) | XMP 내부의 모든  XmpPackage  를 제거합니다. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | 패키지가 xmp 래퍼에 존재하는지 여부를 결정합니다. |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | 헤더 처리 지시문을 가져옵니다. |
| [getMeta()](#getMeta--) | XMP 메타를 가져옵니다. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | 네임스페이스 URI로 패키지를 가져옵니다. |
| [getPackages()](#getPackages--) | XMP 내부의  XmpPackage  배열을 가져옵니다. |
| [getPackagesCount()](#getPackagesCount--) | XMP 구조 내부의 패키지 수를 가져옵니다. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | 루트 RDF 요소를 가져옵니다. |
| [getTrailerPi()](#getTrailerPi--) | 트레일러 처리 지시문을 가져옵니다. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | XMP 값을 XML 표현으로 변환합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | XMP 패키지를 제거합니다. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | 헤더 처리 지시문을 설정합니다. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | XMP 메타를 설정합니다. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | 루트 RDF 요소를 설정합니다. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | 트레일러 처리 지시문을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


새로운  XmpPacketWrapper  클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | 처리 지시문의 XMP 헤더입니다. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | 처리 지시문의 XMP 트레일러입니다. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP 메타데이터입니다. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


새로운  XmpPacketWrapper  클래스 인스턴스를 초기화합니다.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


패키지를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 패키지입니다. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


XMP 내부의 모든  XmpPackage  를 제거합니다.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


패키지가 xmp 래퍼에 존재하는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 패키지 스키마 URI. |

**Returns:**
boolean - 지정된 네임스페이스 URI를 가진 패키지가 XMP 래퍼에 존재하면 true를 반환합니다.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


이 인스턴스를 복제합니다.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


헤더 처리 지시문을 가져옵니다.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


XMP 메타를 가져옵니다. 선택 사항.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


네임스페이스 URI로 패키지를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 패키지 스키마 URI. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


XMP 내부의  XmpPackage  배열을 가져옵니다.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - XMP 내부의  XmpPackage  배열입니다.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


XMP 구조 내부의 패키지 수를 가져옵니다.

**Returns:**
int - XMP 구조 내부의 패키지 수입니다.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


루트 RDF 요소를 가져옵니다.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


트레일러 처리 지시문을 가져옵니다.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


XMP 값을 XML 표현으로 변환합니다.

**Returns:**
java.lang.String - 변환된 XMP 값을 XML로 반환합니다.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


XMP 패키지를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 패키지입니다. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


헤더 처리 지시문을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Header 처리 지시문. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


XMP 메타를 설정합니다. 선택 사항.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP 메타. 선택 사항. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


루트 RDF 요소를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | RDF 루트 요소. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


트레일러 처리 지시문을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Trailer 처리 지시문. |

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

