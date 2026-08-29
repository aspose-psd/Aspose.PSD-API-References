---
title: "SmartObjectResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 파일에서 스마트 오브젝트 레이어에 대한 정보를 포함하는 SmartObjectResource 클래스를 정의합니다."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.ISmartObjectLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/ismartobjectlayerresource)
```
public abstract class SmartObjectResource extends PlacedResource implements ISmartObjectLayerResource
```

SmartObjectResource 클래스를 정의합니다. 이 클래스는 PSD 파일의 스마트 오브젝트 레이어에 대한 정보를 포함합니다. Adobe\\ufffd Photoshop\\ufffd 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용되는 Sold 및 Sole 리소스의 기본 클래스입니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | 안티앨리어싱 정책 키 |
| [BottomKey_internalized](#BottomKey-internalized) | 하단 키 |
| [BoundsKey_internalized](#BoundsKey-internalized) | 경계 키 |
| [CompIdKey_internalized](#CompIdKey-internalized) | CompID의 키 이름 |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | 컴프 정보 키 이름 |
| [CompKey_internalized](#CompKey-internalized) | 컴프 키 |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | ‘none’을 의미하는 컴프 값 |
| [CropKey_internalized](#CropKey-internalized) | 크롭 키 |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | 해당 사용자 지정 엔벨로프 워프 이름 |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | 해당 기본 워프 클래스 이름 |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | 분모 키 |
| [DurationKey_internalized](#DurationKey-internalized) | 지속 시간 키 |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | 해당 기본 워프 클래스 이름 |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | 해당 예상 워프 디스크립터 버전 |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | 해당 예상 워프 버전 |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | 프레임 수 키 |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | 프레임 단계 키 |
| [HeightKey_internalized](#HeightKey-internalized) | 높이 키 |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | 해당 수평 식별자 이름 |
| [IdentKey_internalized](#IdentKey-internalized) | 고유 식별자 키 |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | items 속성은 null일 수 없습니다 |
| [LeftKey_internalized](#LeftKey-internalized) | 왼쪽 키 |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | 해당 메시 포인트 키 이름 |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | 비아핀 변환 키 |
| [NullClassId_internalized](#NullClassId-internalized) | null 클래스 식별자 |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | 분자 키 |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | 옵션 키 컬렉션 |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | 해당 방향 식별자 이름 |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | 원본 CompID의 키 이름 |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | 페이지 번호 키 |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | 배치된 식별자 키 |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | 해당 예상 버전 값 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB 헤더 버전입니다. |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 전용 리소스 서명입니다. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD 헤더 버전입니다. |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | 해당 유리점 클래스 식별자 이름 |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | 해상도 키 |
| [ResourceSignature](#ResourceSignature) | 공통 리소스 서명입니다. |
| [RightKey_internalized](#RightKey-internalized) | 오른쪽 키 |
| [SizeKey_internalized](#SizeKey-internalized) | 크기 키 |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | 해당 double 크기 |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | 해당 int 크기 |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | 예상 스마트 객체 리소스 버전 값. |
| [TopKey_internalized](#TopKey-internalized) | 상단 키 |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | 전체 페이지 수 키 |
| [TransformKey_internalized](#TransformKey-internalized) | 변환 키 |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | 해당 변환 값 개수 |
| [TypeKey_internalized](#TypeKey-internalized) | 타입 키 |
| [TypeValue_internalized](#TypeValue-internalized) | 예상 유형 값. |
| [UOrderKey_internalized](#UOrderKey-internalized) | 해당 u 순서 키 |
| [VOrderKey_internalized](#VOrderKey-internalized) | 해당 v 순서 키 |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | 해당 수직 식별자 이름 |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | 해당 워프 사용자 지정 이름 |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | 해당 워프 헤더 길이. |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | 해당 워프 헤더 길이. |
| [WarpKey_internalized](#WarpKey-internalized) | 해당 워프 키. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | 해당 워프 없음 이름 |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | 해당 워프 원근 키 |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | 해당 워프 원근 기타 |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | 해당 워프 회전 키 |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | 해당 워프 스타일 키 |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | 해당 워프 값 키 |
| [WidthKey_internalized](#WidthKey-internalized) | 너비 키 |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | Crop 속성에 접근할 수 없습니다 메시지 |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | CompId 속성을 설정할 수 없습니다 메시지 |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | Comp 속성을 설정할 수 없습니다 메시지 |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | OriginalCompId 속성을 설정할 수 없습니다 메시지 |
| [ZeroChar_internalized](#ZeroChar-internalized) | 해당 영 문자. |
| [ventureLicense_internalized](#ventureLicense-internalized) | 벤처 라이선스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | 지정된 실제 값이 기대값과 동일함을 확인합니다. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 리소스가 PSB 전용인지 확인하고 설정합니다. |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | 목록 구조를 double 배열로 변환합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 안티앨리어싱 정책을 가져오거나 설정합니다. |
| [getBottom()](#getBottom--) | PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| [getBounds()](#getBounds--) | PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 comp 값을 가져오거나 설정합니다. |
| [getCompId()](#getCompId--) | 자식 문서에 대해 현재 선택된 컴프의 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. |
| [getCrop()](#getCrop--) | PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 crop을 가져오거나 설정합니다. |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Left, Top, Right, Bottom, TransformMatrix와 같은 할당 값에 대한 기본 단위 유형을 가져오거나 설정합니다. |
| [getDurationDenominator()](#getDurationDenominator--) | duration 분모를 가져오거나 설정합니다. |
| [getDurationNumerator()](#getDurationNumerator--) | duration 분자를 가져오거나 설정합니다. |
| [getFrameCount()](#getFrameCount--) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 프레임 수를 가져오거나 설정합니다. |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | frame step 분모를 가져오거나 설정합니다. |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | frame step 분자를 가져오거나 설정합니다. |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getHeight()](#getHeight--) | 높이를 가져오거나 설정합니다. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 수평 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [getItems()](#getItems--) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 descriptor 항목을 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLeft()](#getLeft--) | PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| [getLength()](#getLength--) | 스마트 오브젝트 리소스 길이를 바이트 단위로 가져옵니다. |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 비아핀 변환 행렬을 가져오거나 설정합니다. |
| [getOriginalCompId()](#getOriginalCompId--) | 자식 문서에 대해 현재 선택된 Comp의 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. |
| [getPageNumber()](#getPageNumber--) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 페이지 번호를 가져오거나 설정합니다. |
| [getPerspective()](#getPerspective--) | PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| [getPerspectiveOther()](#getPerspectiveOther--) | PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다. |
| [getPlacedId()](#getPlacedId--) | PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다. |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | PSD 파일의 스마트 오브젝트 레이어 데이터 유형을 가져오거나 설정합니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getResolution()](#getResolution--) | PSD 파일의 스마트 오브젝트 레이어 데이터 해상도를 가져오거나 설정합니다. |
| [getResolutionUnit()](#getResolutionUnit--) | PSD 파일의 스마트 오브젝트 레이어 데이터 해상도 측정 단위를 가져오거나 설정합니다. |
| [getRight()](#getRight--) | PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getTop()](#getTop--) | PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| [getTotalPages()](#getTotalPages--) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 총 페이지 수를 가져오거나 설정합니다. |
| [getTransformMatrix()](#getTransformMatrix--) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 변환 행렬을 가져오거나 설정합니다. |
| [getUOrder()](#getUOrder--) | PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| [getUniqueId()](#getUniqueId--) | PSD 이미지의 스마트 오브젝트 레이어 데이터 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)의 전역 고유 식별자를 가져오거나 설정합니다. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | PSD 파일에 배치된 레이어의 V 순서 값을 가져오거나 설정합니다. |
| [getValue()](#getValue--) | PSD 이미지에 배치된 레이어의 왜곡 값을 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | PSD 파일에 배치된 레이어의 버전을 가져옵니다(보통 3). |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | 수직 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | 클래스 ID를 가져오거나 설정합니다. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | 왜곡 클래스 이름을 가져오거나 설정합니다. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | 워프 디스크립터 버전을 가져오거나 설정합니다. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | 워프 항목. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | 워프 버전을 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 너비를 가져오거나 설정합니다. |
| [get_Item(String index)](#get-Item-java.lang.String-) | 지정된 인덱스에서 [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)를 가져옵니다. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | 이 인스턴스에 경계 단위가 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | 경계와 행렬을 초기화합니다. |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | 이 인스턴스의 회전 방향이 수평인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 스마트 오브젝트 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 안티앨리어싱 정책을 가져오거나 설정합니다. |
| [setBottom(double value)](#setBottom-double-) | PSD 이미지에 배치된 레이어의 하단 위치를 가져오거나 설정합니다. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | PSD 파일에 배치된 레이어의 경계를 가져오거나 설정합니다. |
| [setComp(int value)](#setComp-int-) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 comp 값을 가져오거나 설정합니다. |
| [setCompId(int value)](#setCompId-int-) | 자식 문서에 대해 현재 선택된 컴프의 ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. |
| [setCrop(int value)](#setCrop-int-) | PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 crop을 가져오거나 설정합니다. |
| [setCustom(boolean value)](#setCustom-boolean-) | 이 인스턴스의 워프 스타일이 사용자 지정인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Left, Top, Right, Bottom, TransformMatrix와 같은 할당 값에 대한 기본 단위 유형을 가져오거나 설정합니다. |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | duration 분모를 가져오거나 설정합니다. |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | duration 분자를 가져오거나 설정합니다. |
| [setFrameCount(int value)](#setFrameCount-int-) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 프레임 수를 가져오거나 설정합니다. |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | frame step 분모를 가져오거나 설정합니다. |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | frame step 분자를 가져오거나 설정합니다. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setHeight(double value)](#setHeight-double-) | 높이를 가져오거나 설정합니다. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 수평 메시 포인트의 측정 단위를 가져오거나 설정합니다. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | PSD 파일에 배치된 레이어의 수평 메시 포인트를 가져오거나 설정합니다. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 descriptor 항목을 가져오거나 설정합니다. |
| [setLeft(double value)](#setLeft-double-) | PSD 파일에 배치된 레이어의 왼쪽 위치를 가져오거나 설정합니다. |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 비아핀 변환 행렬을 가져오거나 설정합니다. |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | 자식 문서에 대해 현재 선택된 Comp의 원래 ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. |
| [setPageNumber(int value)](#setPageNumber-int-) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 페이지 번호를 가져오거나 설정합니다. |
| [setPerspective(double value)](#setPerspective-double-) | PSD 파일에 배치된 레이어의 원근값을 가져오거나 설정합니다. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | PSD 파일에 배치된 레이어의 다른 원근값을 가져오거나 설정합니다. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다. |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | PSD 파일의 스마트 오브젝트 레이어 데이터 유형을 가져오거나 설정합니다. |
| [setResolution(double value)](#setResolution-double-) | PSD 파일의 스마트 오브젝트 레이어 데이터 해상도를 가져오거나 설정합니다. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | PSD 파일의 스마트 오브젝트 레이어 데이터 해상도 측정 단위를 가져오거나 설정합니다. |
| [setRight(double value)](#setRight-double-) | PSD 파일에 배치된 레이어의 오른쪽 위치를 가져오거나 설정합니다. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | 이 인스턴스의 회전 방향이 수평인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setTop(double value)](#setTop-double-) | PSD 이미지에 배치된 레이어의 상단 위치를 가져오거나 설정합니다. |
| [setTotalPages(int value)](#setTotalPages-int-) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 총 페이지 수를 가져오거나 설정합니다. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 변환 행렬을 가져오거나 설정합니다. |
| [setUOrder(int value)](#setUOrder-int-) | PSD 파일에 배치된 레이어의 U 순서 값을 가져오거나 설정합니다. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD 이미지의 스마트 오브젝트 레이어 데이터 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)의 전역 고유 식별자를 가져오거나 설정합니다. |
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
| [setWidth(double value)](#setWidth-double-) | 너비를 가져오거나 설정합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


안티앨리어싱 정책 키

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


하단 키

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


경계 키

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


CompID의 키 이름

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


컴프 정보 키 이름

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


컴프 키

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


‘none’을 의미하는 컴프 값

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


크롭 키

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

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


분모 키

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


지속 시간 키

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

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


프레임 수 키

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


프레임 단계 키

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


높이 키

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


해당 수평 식별자 이름

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


고유 식별자 키

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


items 속성은 null일 수 없습니다

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


왼쪽 키

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


해당 메시 포인트 키 이름

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


비아핀 변환 키

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


null 클래스 식별자

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


분자 키

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


옵션 키 컬렉션

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


해당 방향 식별자 이름

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


원본 CompID의 키 이름

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


페이지 번호 키

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


배치된 식별자 키

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

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


해상도 키

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


공통 리소스 서명입니다.

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


오른쪽 키

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


크기 키

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

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


예상 스마트 객체 리소스 버전 값.

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


상단 키

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


전체 페이지 수 키

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


변환 키

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


해당 변환 값 개수

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


타입 키

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


예상 유형 값.

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

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


너비 키

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


Crop 속성에 접근할 수 없습니다 메시지

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


CompId 속성을 설정할 수 없습니다 메시지

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


Comp 속성을 설정할 수 없습니다 메시지

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


OriginalCompId 속성을 설정할 수 없습니다 메시지

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

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


목록 구조를 double 배열로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | ListStructure 인스턴스. |

**Returns:**
double[] - 생성된 double[] 배열.
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


PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 안티앨리어싱 정책을 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어 데이터의 안티앨리어싱 정책.

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
### getComp() {#getComp--}
```
public final int getComp()
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 컴프 값을 가져오거나 설정합니다.  스마트 오브젝트의 레이어 컴프

값: 컴프 값이며, 없을 경우 -1입니다.

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


현재 선택된 자식 문서의 Comp ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. Comp는 디자이너가 만들 수 있는 페이지 레이아웃의 구성을 의미합니다. 레이어 컴프를 사용하면 단일 Adobe\\ufffd Photoshop\\ufffd 파일에서 레이아웃의 여러 버전을 만들고, 관리하고, 볼 수 있습니다. 레이어 컴프는 레이어 패널 상태의 스냅샷입니다. 레이어 컴프는 세 가지 유형의 레이어 옵션을 저장하지만, 이 속성은 PSD 파일의 스마트 오브젝트 레이어에 대한 Layer Comp 선택 식별자를 가져옵니다.  스마트 오브젝트의 레이어 컴프

값: PSD 이미지에서 자식 문서의 현재 선택된 Comp ID이며, 선택된 것이 없으면 -1입니다.

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 crop을 가져오거나 설정합니다.

값: 배치된 레이어 정보의 크롭 값.

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Left, Top, Right, Bottom, TransformMatrix와 같은 할당 값에 대한 기본 단위 유형을 가져오거나 설정합니다.

값: 기본 측정 단위 유형.

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


duration 분모를 가져오거나 설정합니다.

값: 지속 시간의 분모.

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


duration 분자를 가져오거나 설정합니다.

값: 지속 시간의 분자.

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 프레임 수를 가져오거나 설정합니다.

값: 배치된 레이어 정보의 프레임 수.

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


frame step 분모를 가져오거나 설정합니다.

값: 프레임 단계의 분모.

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


frame step 분자를 가져오거나 설정합니다.

값: 프레임 단계의 분자.

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
### getHeight() {#getHeight--}
```
public final double getHeight()
```


높이를 가져오거나 설정합니다.

값: 높이.

**Returns:**
double
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


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 descriptor 항목을 가져오거나 설정합니다.

값: 배치된 레이어 정보의 디스크립터 항목.

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
public int getLength()
```


스마트 오브젝트 리소스 길이를 바이트 단위로 가져옵니다.

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 비아핀 변환 행렬을 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어의 비아핀 변환 행렬.

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


현재 선택된 자식 문서의 원본 Comp ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. 이 속성은 PSD 파일의 스마트 오브젝트 레이어에 대한 원본 레이어 Comp 선택 식별자를 가져옵니다.  스마트 오브젝트의 레이어 컴프

값: PSD 이미지에서 자식 문서의 현재 선택된 Comp의 원본 ID이며, 선택된 것이 없으면 -1입니다.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 페이지 번호를 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어 데이터의 페이지 번호.

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
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다.

값: 이 스마트 오브젝트 레이어 리소스의 고유 식별자.

**Returns:**
java.util.UUID
### getPlacedId_internalized() {#getPlacedId-internalized--}
```
public final System.Guid getPlacedId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


PSD 파일의 스마트 오브젝트 레이어 데이터 유형을 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어 데이터의 유형.

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
### getResolution() {#getResolution--}
```
public final double getResolution()
```


PSD 파일의 스마트 오브젝트 레이어 데이터 해상도를 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어의 해상도.

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


PSD 파일의 스마트 오브젝트 레이어 데이터 해상도 측정 단위를 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어의 해상도 측정 단위.

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


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 총 페이지 수를 가져오거나 설정합니다.

값: 스마트 객체 레이어 데이터의 전체 페이지 수.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 변환 행렬을 가져오거나 설정합니다.

값: 스마트 객체 레이어 데이터의 변환 행렬.

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


PSD 이미지의 스마트 오브젝트 레이어 데이터 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)의 전역 고유 식별자를 가져오거나 설정합니다.

값: 스마트 객체 레이어 데이터의 전역 고유 식별자 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

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


워프 항목.

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
### getWidth() {#getWidth--}
```
public final double getWidth()
```


너비를 가져오거나 설정합니다.

값: 너비.

**Returns:**
double
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

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


경계와 행렬을 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 경계. |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




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
public void save(StreamContainer streamContainer, int psdVersion)
```


스마트 오브젝트 리소스를 지정된 스트림 컨테이너에 저장합니다.

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


PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 안티앨리어싱 정책을 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어 데이터의 안티앨리어싱 정책.

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

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 컴프 값을 가져오거나 설정합니다.  스마트 오브젝트의 레이어 컴프

값: 컴프 값이며, 없을 경우 -1입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


현재 선택된 자식 문서의 Comp ID를 가져오거나 설정합니다. 선택된 것이 없으면 -1이 됩니다. Comp는 디자이너가 만들 수 있는 페이지 레이아웃의 구성을 의미합니다. 레이어 컴프를 사용하면 단일 Adobe\\ufffd Photoshop\\ufffd 파일에서 레이아웃의 여러 버전을 만들고, 관리하고, 볼 수 있습니다. 레이어 컴프는 레이어 패널 상태의 스냅샷입니다. 레이어 컴프는 세 가지 유형의 레이어 옵션을 저장하지만, 이 속성은 PSD 파일의 스마트 오브젝트 레이어에 대한 Layer Comp 선택 식별자를 가져옵니다.  스마트 오브젝트의 레이어 컴프

값: PSD 이미지에서 자식 문서의 현재 선택된 Comp ID이며, 선택된 것이 없으면 -1입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


PSD 이미지의 스마트 오브젝트 레이어 데이터에 대한 crop을 가져오거나 설정합니다.

값: 배치된 레이어 정보의 크롭 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


duration 분모를 가져오거나 설정합니다.

값: 지속 시간의 분모.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


duration 분자를 가져오거나 설정합니다.

값: 지속 시간의 분자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 프레임 수를 가져오거나 설정합니다.

값: 배치된 레이어 정보의 프레임 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


frame step 분모를 가져오거나 설정합니다.

값: 프레임 단계의 분모.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


frame step 분자를 가져오거나 설정합니다.

값: 프레임 단계의 분자.

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

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


높이를 가져오거나 설정합니다.

값: 높이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 descriptor 항목을 가져오거나 설정합니다.

값: 배치된 레이어 정보의 디스크립터 항목.

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

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 비아핀 변환 행렬을 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어의 비아핀 변환 행렬.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


현재 선택된 자식 문서의 원본 Comp ID를 가져옵니다. 선택된 것이 없으면 -1이 됩니다. 이 속성은 PSD 파일의 스마트 오브젝트 레이어에 대한 원본 레이어 Comp 선택 식별자를 가져옵니다.  스마트 오브젝트의 레이어 컴프

값: PSD 이미지에서 자식 문서의 현재 선택된 Comp의 원본 ID이며, 선택된 것이 없으면 -1입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 페이지 번호를 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어 데이터의 페이지 번호.

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

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


PSD 이미지의 이 스마트 오브젝트 레이어 데이터에 대한 고유 식별자를 가져오거나 설정합니다.

값: 이 스마트 오브젝트 레이어 리소스의 고유 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터 유형을 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어 데이터의 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터 해상도를 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어의 해상도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터 해상도 측정 단위를 가져오거나 설정합니다.

값: 스마트 오브젝트 레이어의 해상도 측정 단위.

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


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 총 페이지 수를 가져오거나 설정합니다.

값: 스마트 객체 레이어 데이터의 전체 페이지 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


PSD 파일의 스마트 오브젝트 레이어 데이터에 대한 변환 행렬을 가져오거나 설정합니다.

값: 스마트 객체 레이어 데이터의 변환 행렬.

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


PSD 이미지의 스마트 오브젝트 레이어 데이터 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)의 전역 고유 식별자를 가져오거나 설정합니다.

값: 스마트 객체 레이어 데이터의 전역 고유 식별자 [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

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

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


너비를 가져오거나 설정합니다.

값: 너비.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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

