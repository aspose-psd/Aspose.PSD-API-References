---
title: "ArtDResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "PsdImage.GlobalLayerResources에 대한 아트보드 정보 데이터입니다/."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtDResource extends BaseArtboardInfoResource
```

PsdImage.GlobalLayerResources에 대한 아트보드 정보 데이터입니다 ([PsdImage.getGlobalLayerResources](../../com.aspose.psd.fileformats.psd/psdimage\#getGlobalLayerResources)/[PsdImage.setGlobalLayerResources(LayerResource[])](../../com.aspose.psd.fileformats.psd/psdimage\#setGlobalLayerResources-LayerResource---)).
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ArtDResource()](#ArtDResource--) | 새 인스턴스를 초기화합니다 [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) 클래스. |
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
| [getArtboardCount_internalized()](#getArtboardCount-internalized--) | Art-boards의 개수를 가져오거나 설정합니다. |
| [getAutoExpandOffset_internalized()](#getAutoExpandOffset-internalized--) | 자동 확장 오프셋을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | 리소스 클래스 ID를 가져오거나 설정합니다. |
| [getClassName_internalized()](#getClassName-internalized--) | 리소스 클래스 이름을 가져오거나 설정합니다. |
| [getDocDefaultNewArtboardBackgroundColor_internalized()](#getDocDefaultNewArtboardBackgroundColor-internalized--) | DocDefaultNewArtboardBackgroundColor를 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [getDocDefaultNewArtboardBackgroundType_internalized()](#getDocDefaultNewArtboardBackgroundType-internalized--) | DocDefaultNewArtboardBackgroundType을 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)). |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getItems()](#getItems--) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 항목을 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) |    |
| [getOriginPoint_internalized()](#getOriginPoint-internalized--) | 원점 좌표를 가져오거나 설정합니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getVersion_internalized()](#getVersion-internalized--) | 리소스 버전을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isAutoExpandEnabled_internalized()](#isAutoExpandEnabled-internalized--) | IsAutoExpandEnabled를 가져오거나 설정합니다 ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [isAutoNestEnabled_internalized()](#isAutoNestEnabled-internalized--) | IsAutoNestEnabled를 가져오거나 설정합니다 ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [isAutoPositionEnabled_internalized()](#isAutoPositionEnabled-internalized--) | IsAutoPositionEnabled를 가져오거나 설정합니다 ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [isShrinkwrapOnSaveEnabled_internalized()](#isShrinkwrapOnSaveEnabled-internalized--) | IsShrinkwrapOnSaveEnabled를 가져오거나 설정합니다 ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setArtboardCount_internalized(int value)](#setArtboardCount-internalized-int-) | Art-boards의 개수를 가져오거나 설정합니다. |
| [setAutoExpandEnabled_internalized(boolean value)](#setAutoExpandEnabled-internalized-boolean-) | IsAutoExpandEnabled를 가져오거나 설정합니다 ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [setAutoExpandOffset_internalized(PointF value)](#setAutoExpandOffset-internalized-com.aspose.psd.PointF-) | 자동 확장 오프셋을 가져오거나 설정합니다. |
| [setAutoNestEnabled_internalized(boolean value)](#setAutoNestEnabled-internalized-boolean-) | IsAutoNestEnabled를 가져오거나 설정합니다 ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [setAutoPositionEnabled_internalized(boolean value)](#setAutoPositionEnabled-internalized-boolean-) | IsAutoPositionEnabled를 가져오거나 설정합니다 ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 리소스 클래스 ID를 가져오거나 설정합니다. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | 리소스 클래스 이름을 가져오거나 설정합니다. |
| [setDocDefaultNewArtboardBackgroundColor_internalized(Color value)](#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-) | DocDefaultNewArtboardBackgroundColor를 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [setDocDefaultNewArtboardBackgroundType_internalized(int value)](#setDocDefaultNewArtboardBackgroundType-internalized-int-) | DocDefaultNewArtboardBackgroundType을 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)). |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) 항목을 가져오거나 설정합니다. |
| [setOriginPoint_internalized(PointF value)](#setOriginPoint-internalized-com.aspose.psd.PointF-) | 원점 좌표를 가져오거나 설정합니다. |
| [setShrinkwrapOnSaveEnabled_internalized(boolean value)](#setShrinkwrapOnSaveEnabled-internalized-boolean-) | IsShrinkwrapOnSaveEnabled를 가져오거나 설정합니다 ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | 리소스 버전을 가져오거나 설정합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtDResource() {#ArtDResource--}
```
public ArtDResource()
```


새 인스턴스를 초기화합니다 [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) 클래스.

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
### getArtboardCount_internalized() {#getArtboardCount-internalized--}
```
public final int getArtboardCount_internalized()
```


Art-boards의 개수를 가져오거나 설정합니다.

**Returns:**
int
### getAutoExpandOffset_internalized() {#getAutoExpandOffset-internalized--}
```
public final PointF getAutoExpandOffset_internalized()
```


자동 확장 오프셋을 가져오거나 설정합니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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
### getDocDefaultNewArtboardBackgroundColor_internalized() {#getDocDefaultNewArtboardBackgroundColor-internalized--}
```
public final Color getDocDefaultNewArtboardBackgroundColor_internalized()
```


DocDefaultNewArtboardBackgroundColor를 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Returns:**
[Color](../../com.aspose.psd/color)
### getDocDefaultNewArtboardBackgroundType_internalized() {#getDocDefaultNewArtboardBackgroundType-internalized--}
```
public final int getDocDefaultNewArtboardBackgroundType_internalized()
```


DocDefaultNewArtboardBackgroundType을 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)).

**Returns:**
int
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
### getOriginPoint_internalized() {#getOriginPoint-internalized--}
```
public final PointF getOriginPoint_internalized()
```


원점 좌표를 가져오거나 설정합니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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
### isAutoExpandEnabled_internalized() {#isAutoExpandEnabled-internalized--}
```
public final boolean isAutoExpandEnabled_internalized()
```


IsAutoExpandEnabled를 가져오거나 설정합니다 ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoNestEnabled_internalized() {#isAutoNestEnabled-internalized--}
```
public final boolean isAutoNestEnabled_internalized()
```


IsAutoNestEnabled를 가져오거나 설정합니다 ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoPositionEnabled_internalized() {#isAutoPositionEnabled-internalized--}
```
public final boolean isAutoPositionEnabled_internalized()
```


IsAutoPositionEnabled를 가져오거나 설정합니다 ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

**Returns:**
boolean
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
### isShrinkwrapOnSaveEnabled_internalized() {#isShrinkwrapOnSaveEnabled-internalized--}
```
public final boolean isShrinkwrapOnSaveEnabled_internalized()
```


IsShrinkwrapOnSaveEnabled를 가져오거나 설정합니다 ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

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

### setArtboardCount_internalized(int value) {#setArtboardCount-internalized-int-}
```
public final void setArtboardCount_internalized(int value)
```


Art-boards의 개수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setAutoExpandEnabled_internalized(boolean value) {#setAutoExpandEnabled-internalized-boolean-}
```
public final void setAutoExpandEnabled_internalized(boolean value)
```


IsAutoExpandEnabled를 가져오거나 설정합니다 ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAutoExpandOffset_internalized(PointF value) {#setAutoExpandOffset-internalized-com.aspose.psd.PointF-}
```
public final void setAutoExpandOffset_internalized(PointF value)
```


자동 확장 오프셋을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setAutoNestEnabled_internalized(boolean value) {#setAutoNestEnabled-internalized-boolean-}
```
public final void setAutoNestEnabled_internalized(boolean value)
```


IsAutoNestEnabled를 가져오거나 설정합니다 ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAutoPositionEnabled_internalized(boolean value) {#setAutoPositionEnabled-internalized-boolean-}
```
public final void setAutoPositionEnabled_internalized(boolean value)
```


IsAutoPositionEnabled를 가져오거나 설정합니다 ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

### setDocDefaultNewArtboardBackgroundColor_internalized(Color value) {#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-}
```
public final void setDocDefaultNewArtboardBackgroundColor_internalized(Color value)
```


DocDefaultNewArtboardBackgroundColor를 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDocDefaultNewArtboardBackgroundType_internalized(int value) {#setDocDefaultNewArtboardBackgroundType-internalized-int-}
```
public final void setDocDefaultNewArtboardBackgroundType_internalized(int value)
```


DocDefaultNewArtboardBackgroundType을 가져오거나 설정합니다 ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setOriginPoint_internalized(PointF value) {#setOriginPoint-internalized-com.aspose.psd.PointF-}
```
public final void setOriginPoint_internalized(PointF value)
```


원점 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setShrinkwrapOnSaveEnabled_internalized(boolean value) {#setShrinkwrapOnSaveEnabled-internalized-boolean-}
```
public final void setShrinkwrapOnSaveEnabled_internalized(boolean value)
```


IsShrinkwrapOnSaveEnabled를 가져오거나 설정합니다 ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

