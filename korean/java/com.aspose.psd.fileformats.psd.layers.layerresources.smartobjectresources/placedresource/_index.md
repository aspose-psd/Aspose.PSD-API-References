---
title: "PlacedResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 파일에서 배치된 레이어 또는 스마트 오브젝트 레이어에 대한 일반 정보를 포함하는 PlacedResource 클래스를 정의합니다."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

PlacedResource 클래스를 정의하며 PSD 파일에서 배치 레이어 또는 스마트 오브젝트 레이어에 대한 일반 정보를 포함합니다. 이 클래스는 Adobe\\ufffd Photoshop\\ufffd 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | 해당 사용자 지정 엔벨로프 워프 이름 |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | 해당 기본 워프 클래스 이름 |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | 해당 기본 워프 클래스 이름 |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | 해당 예상 워프 디스크립터 버전 |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | 해당 예상 워프 버전 |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | 해당 수평 식별자 이름 |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | 해당 메시 포인트 키 이름 |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | 해당 방향 식별자 이름 |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | 해당 예상 버전 값 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB 헤더 버전입니다. |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 전용 리소스 서명입니다. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD 헤더 버전입니다. |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | 해당 유리점 클래스 식별자 이름 |
| [ResourceSignature](#ResourceSignature) | 공통 리소스 서명입니다. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | 해당 double 크기 |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | 해당 int 크기 |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | 해당 변환 값 개수 |
| [UOrderKey_internalized](#UOrderKey-internalized) | 해당 u 순서 키 |
| [VOrderKey_internalized](#VOrderKey-internalized) | 해당 v 순서 키 |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | 해당 수직 식별자 이름 |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | 해당 워프 사용자 지정 이름 |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | 해당 워프 헤더 길이. |
| [WarpKey_internalized](#WarpKey-internalized) | 해당 워프 키. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | 해당 워프 없음 이름 |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | 해당 워프 원근 키 |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | 해당 워프 원근 기타 |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | 해당 워프 회전 키 |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | 해당 워프 스타일 키 |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | 해당 워프 값 키 |
| [ZeroChar_internalized](#ZeroChar-internalized) | 해당 영 문자. |
| [ventureLicense_internalized](#ventureLicense-internalized) | 벤처 라이선스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | 지정된 실제 값이 기대값과 동일함을 확인합니다. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 리소스가 PSB 전용인지 확인하고 설정합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다. |
| [getBottom()](#getBottom--) | PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| [getBounds()](#getBounds--) | PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Left, Top, Right, Bottom, TransformMatrix와 같은 할당 값에 대한 기본 단위 유형을 가져오거나 설정합니다. |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 수평 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [getItems()](#getItems--) | 왜곡 항목을 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLeft()](#getLeft--) | PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getPageNumber()](#getPageNumber--) | PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다. |
| [getPerspective()](#getPerspective--) | PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| [getPerspectiveOther()](#getPerspectiveOther--) | PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다. |
| [getPlacedLayerType()](#getPlacedLayerType--) | PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getRight()](#getRight--) | PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getTop()](#getTop--) | PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| [getTotalPages()](#getTotalPages--) | PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다. |
| [getTransformMatrix()](#getTransformMatrix--) | PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다. |
| [getUOrder()](#getUOrder--) | PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| [getUniqueId()](#getUniqueId--) | PSD 이미지에 배치된 레이어의 전역 고유 식별자를 가져오거나 설정합니다. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| [getValue()](#getValue--) | PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | PSD 파일에 배치된 레이어의 버전을 가져옵니다(보통 3). |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | 수직 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | 클래스 ID를 가져오거나 설정합니다. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | 왜곡 클래스 이름을 가져오거나 설정합니다. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | 워프 디스크립터 버전을 가져오거나 설정합니다. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | 왜곡 항목을 가져오거나 설정합니다. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | 워프 버전을 가져오거나 설정합니다. |
| [get_Item(String index)](#get-Item-java.lang.String-) | 지정된 인덱스에서 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)를 가져옵니다. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | 이 인스턴스에 경계 단위가 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | 이 인스턴스의 회전 방향이 수평인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다. |
| [setBottom(double value)](#setBottom-double-) | PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다. |
| [setCustom(boolean value)](#setCustom-boolean-) | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Left, Top, Right, Bottom, TransformMatrix와 같은 할당 값에 대한 기본 단위 유형을 가져오거나 설정합니다. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 수평 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 왜곡 항목을 가져오거나 설정합니다. |
| [setLeft(double value)](#setLeft-double-) | PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| [setPageNumber(int value)](#setPageNumber-int-) | PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다. |
| [setPerspective(double value)](#setPerspective-double-) | PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다. |
| [setRight(double value)](#setRight-double-) | PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | 이 인스턴스의 회전 방향이 수평인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setTop(double value)](#setTop-double-) | PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| [setTotalPages(int value)](#setTotalPages-int-) | PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다. |
| [setUOrder(int value)](#setUOrder-int-) | PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD 이미지에 배치된 레이어의 전역 고유 식별자를 가져오거나 설정합니다. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| [setValue(double value)](#setValue-double-) | PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다. |
| [setVersion(int value)](#setVersion-int-) | PSD 파일에 배치된 레이어의 버전을 가져옵니다(보통 3). |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | 수직 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | 클래스 ID를 가져오거나 설정합니다. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | 왜곡 클래스 이름을 가져오거나 설정합니다. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | 워프 디스크립터 버전을 가져오거나 설정합니다. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | 워프 버전을 가져오거나 설정합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


해당 사용자 지정 엔벨로프 워프 이름

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


해당 기본 워프 클래스 이름

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


해당 기본 워프 클래스 이름

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


해당 예상 워프 디스크립터 버전

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


해당 예상 워프 버전

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


해당 수평 식별자 이름

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


해당 메시 포인트 키 이름

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


해당 방향 식별자 이름

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


해당 예상 버전 값

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

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


해당 유리점 클래스 식별자 이름

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


공통 리소스 서명입니다.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


해당 double 크기

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


해당 int 크기

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


해당 변환 값 개수

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


해당 u 순서 키

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


해당 v 순서 키

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


해당 수직 식별자 이름

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


해당 워프 사용자 지정 이름

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


해당 워프 헤더 길이.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


워프 키입니다. 또한 기본 워프 클래스 이름입니다.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


해당 워프 없음 이름

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


해당 워프 원근 키

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


해당 워프 원근 기타

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


해당 워프 회전 키

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


해당 워프 스타일 키

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


해당 워프 값 키

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


해당 영 문자.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


벤처 라이선스.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


지정된 실제 값이 기대값과 동일함을 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| actualValue | java.lang.Object | 실제 값입니다. |
| expectedValue | java.lang.Object | 예상 값입니다. |
| message | java.lang.String | 메시지. |

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
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다.

값: 배치된 레이어의 anti alias 정책.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 하단 위치.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다.

값: 배치된 레이어 경계.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Left, Top, Right, Bottom, TransformMatrix와 같은 할당 값에 대한 기본 단위 유형을 가져오거나 설정합니다.

값: 기본 측정 단위 유형.

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
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


수평 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수평 메시 포인트의 측정 단위.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


왜곡 항목을 가져오거나 설정합니다.

값: 워프 항목.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


레이어 리소스 키를 가져옵니다.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 왼쪽 위치.

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


레이어 리소스 길이를 바이트 단위로 가져옵니다.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다.

값: 배치된 레이어의 페이지 번호.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 원근값.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 다른 원근값.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다.

값: 배치된 레이어의 유형.

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
### getRight() {#getRight--}
```
public final double getRight()
```


PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 오른쪽 위치.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


레이어 리소스 서명을 가져옵니다.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 상단 위치.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다.

값: 배치된 레이어의 총 페이지 수.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다.

값: 배치된 레이어의 변환 행렬.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 U 차수 값.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


PSD 이미지에 배치된 레이어의 전역 고유 식별자를 가져오거나 설정합니다.

값: 배치된 레이어의 고유 식별자.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 V 차수 값.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다.

값: 배치된 레이어의 왜곡 값.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


PSD 파일에 배치된 레이어의 버전을 가져옵니다(보통 3).

값: 배치된 레이어 버전.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


수직 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수직 메쉬 포인트의 측정 단위.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


클래스 ID를 가져오거나 설정합니다.

값: 클래스 ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


왜곡 클래스 이름을 가져오거나 설정합니다.

값: 왜곡 클래스 이름.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


워프 디스크립터 버전을 가져오거나 설정합니다.

값: 왜곡 디스크립터 버전.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


왜곡 항목을 가져오거나 설정합니다.

값: 워프 항목.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


워프 버전을 가져오거나 설정합니다.

값: 왜곡 버전.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


지정된 인덱스에서 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | java.lang.String | 키 이름. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


이 인스턴스에 경계 단위가 있는지 여부를 나타내는 값을 가져옵니다.

값:  true  이 인스턴스에 경계 단위가 있으면; 그렇지 않으면  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


이 인스턴스의 왜곡 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. true이면 메쉬 포인트를 포함합니다. false로 설정하면 메쉬 포인트를 지웁니다.

값:  true  배치된 레이어에 사용자 지정 스타일이 있으면; 그렇지 않으면  false .

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
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


이 인스턴스의 회전 방향이 수평인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  회전 방향이 수평이면; 그렇지 않으면  false .

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
public abstract void save(StreamContainer streamContainer, int psdVersion)
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

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


PSD 이미지에 배치된 레이어의 안티앨리어싱 정책을 가져오거나 설정합니다.

값: 배치된 레이어의 anti alias 정책.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 하단 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다.

값: 배치된 레이어 경계.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


이 인스턴스의 왜곡 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. true이면 메쉬 포인트를 포함합니다. false로 설정하면 메쉬 포인트를 지웁니다.

값:  true  배치된 레이어에 사용자 지정 스타일이 있으면; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Left, Top, Right, Bottom, TransformMatrix와 같은 할당 값에 대한 기본 단위 유형을 가져오거나 설정합니다.

값: 기본 측정 단위 유형.

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

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


수평 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수평 메시 포인트의 측정 단위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


왜곡 항목을 가져오거나 설정합니다.

값: 워프 항목.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 왼쪽 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


PSD 파일에 배치된 레이어의 페이지 번호를 가져오거나 설정합니다.

값: 배치된 레이어의 페이지 번호.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 원근값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다.

값: 배치된 레이어의 다른 원근값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


PSD 파일에 배치된 레이어의 유형을 가져오거나 설정합니다.

값: 배치된 레이어의 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 오른쪽 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


이 인스턴스의 회전 방향이 수평인지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  회전 방향이 수평이면; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다.

값: 배치된 레이어의 상단 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


PSD 파일에 배치된 레이어의 전체 페이지 수를 가져오거나 설정합니다.

값: 배치된 레이어의 총 페이지 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


PSD 파일에 배치된 레이어의 변환 행렬을 가져오거나 설정합니다.

값: 배치된 레이어의 변환 행렬.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 U 차수 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


PSD 이미지에 배치된 레이어의 전역 고유 식별자를 가져오거나 설정합니다.

값: 배치된 레이어의 고유 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다.

값: 배치된 레이어의 V 차수 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다.

값: 배치된 레이어의 왜곡 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


PSD 파일에 배치된 레이어의 버전을 가져옵니다(보통 3).

값: 배치된 레이어 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


수직 메시 포인트의 측정 단위를 가져오거나 설정합니다.

값: 수직 메쉬 포인트의 측정 단위.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다.

값: 배치된 레이어의 수평 메시 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


클래스 ID를 가져오거나 설정합니다.

값: 클래스 ID.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


왜곡 클래스 이름을 가져오거나 설정합니다.

값: 왜곡 클래스 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


워프 디스크립터 버전을 가져오거나 설정합니다.

값: 왜곡 디스크립터 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


워프 버전을 가져오거나 설정합니다.

값: 왜곡 버전.

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

