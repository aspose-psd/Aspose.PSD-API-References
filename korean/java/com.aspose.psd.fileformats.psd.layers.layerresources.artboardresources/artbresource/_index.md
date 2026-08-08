---
title: "ArtBResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "Layer.Resources에 대한 아트보드 정보 데이터/."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtBResource extends BaseArtboardInfoResource
```

Layer.Resources에 대한 아트보드 정보 데이터 ([Layer.getResources](../../com.aspose.psd.fileformats.psd.layers/layer\#getResources)/[Layer.setResources(LayerResource[])](../../com.aspose.psd.fileformats.psd.layers/layer\#setResources-LayerResource---)).
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ArtBResource()](#ArtBResource--) | 새 인스턴스를 초기화합니다 [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource) 클래스. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB 헤더 버전입니다. |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 전용 리소스 서명입니다. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD 헤더 버전입니다. |
| [ResourceSignature](#ResourceSignature) | 공통 리소스 서명입니다. |
| [TypeToolKey](#TypeToolKey) | 타입 도구 정보 키. |
| [ventureLicense_internalized](#ventureLicense-internalized) | 벤처 라이선스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 리소스가 PSB 전용인지 확인하고 설정합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtboardBackgroundType()](#getArtboardBackgroundType--) | ArtboardBackgroundType을 가져오거나 설정합니다 ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [getArtboardPresetName_internalized()](#getArtboardPresetName-internalized--) | ArtboardPresetName을 가져오거나 설정합니다 ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [getArtboardRect_internalized()](#getArtboardRect-internalized--) | ArtboardRect을 가져오거나 설정합니다 ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | 리소스 클래스 ID를 가져오거나 설정합니다. |
| [getClassName_internalized()](#getClassName-internalized--) | 리소스 클래스 이름을 가져오거나 설정합니다. |
| [getColor()](#getColor--) | Color를 가져오거나 설정합니다 ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [getGuideIndeces_internalized()](#getGuideIndeces-internalized--) | GuideIndeces를 가져오거나 설정합니다 ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getItems()](#getItems--) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 항목을 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) |    |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getVersion_internalized()](#getVersion-internalized--) | 리소스 버전을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setArtboardBackgroundType(int value)](#setArtboardBackgroundType-int-) | ArtboardBackgroundType을 가져오거나 설정합니다 ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [setArtboardPresetName_internalized(String value)](#setArtboardPresetName-internalized-java.lang.String-) | ArtboardPresetName을 가져오거나 설정합니다 ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [setArtboardRect_internalized(RectangleF value)](#setArtboardRect-internalized-com.aspose.psd.RectangleF-) | ArtboardRect을 가져오거나 설정합니다 ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 리소스 클래스 ID를 가져오거나 설정합니다. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | 리소스 클래스 이름을 가져오거나 설정합니다. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Color를 가져오거나 설정합니다 ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)](#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | GuideIndeces를 가져오거나 설정합니다 ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 항목을 가져오거나 설정합니다. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | 리소스 버전을 가져오거나 설정합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtBResource() {#ArtBResource--}
```
public ArtBResource()
```


새 인스턴스를 초기화합니다 [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource) 클래스.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB 헤더 버전입니다.

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB 전용 리소스 서명입니다.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD 헤더 버전입니다.

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


공통 리소스 서명입니다.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


타입 도구 정보 키.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


벤처 라이선스.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


리소스가 PSB 전용인지 확인하고 설정합니다. 현재 일부 리소스는 인식되지 않지만, 저장 시 동작이 변경되는 PSB 전용 리소스 전체 목록이 있습니다. 따라서 최소한 UnknownResource에서 이를 확인해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | int | 키. |

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
### getArtboardBackgroundType() {#getArtboardBackgroundType--}
```
public final int getArtboardBackgroundType()
```


ArtboardBackgroundType을 가져오거나 설정합니다 ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Returns:**
int
### getArtboardPresetName_internalized() {#getArtboardPresetName-internalized--}
```
public final String getArtboardPresetName_internalized()
```


ArtboardPresetName을 가져오거나 설정합니다 ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Returns:**
java.lang.String
### getArtboardRect_internalized() {#getArtboardRect-internalized--}
```
public final RectangleF getArtboardRect_internalized()
```


ArtboardRect을 가져오거나 설정합니다 ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


리소스 클래스 ID를 가져오거나 설정합니다.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


리소스 클래스 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String
### getColor() {#getColor--}
```
public final Color getColor()
```


Color를 가져오거나 설정합니다 ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Returns:**
[Color](../../com.aspose.psd/color)
### getGuideIndeces_internalized() {#getGuideIndeces-internalized--}
```
public final System.Collections.Generic.List<OSTypeStructure> getGuideIndeces_internalized()
```


GuideIndeces를 가져오거나 설정합니다 ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure>
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


헤더를 가져오거나 설정합니다.

값: 헤더.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 항목을 가져오거나 설정합니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


레이어 리소스 키를 가져옵니다.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


  

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


접두사 길이를 가져옵니다. 기본값은 8BIM 리소스의 경우 12이며, 8B64의 경우 16입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| psdVersion | int | PSD 버전. |

**Returns:**
int - 접두사 길이.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


레이어 리소스 서명을 가져옵니다.

**Returns:**
int
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


리소스 버전을 가져오거나 설정합니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


리소스가 PSB 전용인지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | int | 리소스 키. |

**Returns:**
boolean -  true  리소스가 PSB 전용이면; 그렇지 않으면,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다.

값:  true  이 인스턴스가 리소스 PSB 전용이면; 그렇지 않으면,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


지정된 스트림 컨테이너에 리소스를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psdVersion | int | PSD 버전. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


사용자 정의 리소스 헤더를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| 시그니처 | int | 서명. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


헤더 서명, 식별자 및 길이를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| 시그니처 | int | 서명. |
| isLengthLong | boolean | 설정된 경우  true  길이가 깁니다. |

### setArtboardBackgroundType(int value) {#setArtboardBackgroundType-int-}
```
public final void setArtboardBackgroundType(int value)
```


ArtboardBackgroundType을 가져오거나 설정합니다 ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setArtboardPresetName_internalized(String value) {#setArtboardPresetName-internalized-java.lang.String-}
```
public final void setArtboardPresetName_internalized(String value)
```


ArtboardPresetName을 가져오거나 설정합니다 ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setArtboardRect_internalized(RectangleF value) {#setArtboardRect-internalized-com.aspose.psd.RectangleF-}
```
public final void setArtboardRect_internalized(RectangleF value)
```


ArtboardRect을 가져오거나 설정합니다 ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


리소스 클래스 ID를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


리소스 클래스 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Color를 가져오거나 설정합니다 ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value) {#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public final void setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)
```


GuideIndeces를 가져오거나 설정합니다 ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


헤더를 가져오거나 설정합니다.

값: 헤더.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 항목을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


리소스 버전을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 문자열.
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

