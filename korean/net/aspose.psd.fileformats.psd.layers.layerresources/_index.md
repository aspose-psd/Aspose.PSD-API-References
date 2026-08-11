---
title: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "네임스페이스에는 레이어에 포함된 PSD 파일 형식 엔터티가 포함되어 있습니다."
type: docs
weight: 300
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/
---
{{< psd/tize >}}
네임스페이스에는 레이어에 포함된 PSD 파일 형식 엔터티가 포함되어 있습니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [AbddResource](./abddresource/) | 아트보드 정보 데이터. |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | 조정 레이어 리소스를 위한 기본 클래스 |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | 애니메이션 데이터가 포함된 섹션. |
| [ArtBResource](./artbresource/) | [`Resources`](../aspose.psd.fileformats.psd.layers/layer/resources/)에 대한 아트보드 정보 데이터. |
| [ArtDResource](./artdresource/) | [`GlobalLayerResources`](../aspose.psd.fileformats.psd/psdimage/globallayerresources/)에 대한 아트보드 정보 데이터. |
| [BaseArtboardInfoResource](./baseartboardinforesource/) | 아트보드 정보 데이터 리소스. |
| [BaseFxResource](./basefxresource/) | 기본 효과 리소스 |
| [BaseLayerSectionResource](./baselayersectionresource/) | 레이어 섹션 리소스를 위한 기본 클래스 |
| [BlncResource](./blncresource/) | BlncResource 클래스는 색상 조정 레이어의 리소스입니다. |
| [BlwhResource](./blwhresource/) | BlwhResource 클래스는 흑백 조정 레이어의 리소스입니다. |
| [BooleanResource](./booleanresource/) | BooleanResource 클래스. 이것은 가상 리소스이며, Photoshop에는 없습니다. |
| [BritResource](./britresource/) | BritResource 클래스. 밝기/대비 조정 레이어의 리소스 |
| [CgEdResource](./cgedresource/) | CgEdResource 클래스. 콘텐츠 생성기 추가 데이터 (Photoshop CS5) |
| [ClassID](./classid/) | PSD 클래스 ID 객체. |
| [ClblResource](./clblresource/) | ClblResource 클래스. 이 리소스는 클리핑된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [CmlsResource](./cmlsresource/) | CmlsResource 클래스. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/)에는 HSV 매개변수를 변경할 수 있는 6개의 색상 범위가 있습니다. 각 범위에는 범위 경계를 식별하는 4개의 키 포인트가 있습니다. 그리고 이것은 ColorRangeHsl입니다. |
| [CurvesContinuousManager](./curvescontinuousmanager/) | 곡선을 조작하는 Curves Adjustment Layer 매니저 |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | 픽셀 맵을 조작하는 Curves Adjustment Layer 매니저 |
| [CurvesManager](./curvesmanager/) | CurvResource를 관리하기 위한 기본 클래스 |
| [CurvResource](./curvresource/) | CurvResource 클래스. Curves Adjustment Layer의 리소스 1 바이트 - 곡선을 사용할 경우 0, 픽셀 맵을 사용할 경우 1. 0인 경우: 2 바이트 - short. 기본값은 1. 4 바이트 - int. 비트별로 마지막 바이트만 사용. 첫 번째 비트는 1채널, 네 번째 비트는 4채널을 나타냅니다. 예시: 2 바이트 - short 포인트 수. 4 바이트 * 포인트 수 - 곡선 포인트. 2 short: 첫 번째 위치, 두 번째 높이. 4 바이트 - word "Crv " 2 바이트 - short, 기본값은 Curves의 경우 4. 4 바이트 - int, 기본값은 1. 4 바이트 - 포인트 수. 4 바이트 * 포인트 수 - 곡선 포인트. 2 short: 첫 번째 위치, 두 번째 높이. 0-4 바이트 - 네 개가 접히도록. 1인 경우: 2 바이트 - short, 기본값은 1. 4 바이트 - int, 마지막 바이트만 사용. 하나의 채널은 한 비트에 해당합니다. 첫 번째 비트는 1채널, 네 번째 비트는 4채널을 나타냅니다. 예시: 256 * 변경된 채널 수 - 0~255 범위의 정렬된 채널 값. 4 바이트 - word "Crv " 2 바이트 - short, 기본값은 픽셀 맵의 경우 3. 4 바이트 - int 채널 수 (2 + 256) 바이트 - short, 채널 인덱스용 2 바이트, 256은 0~255 범위의 정렬된 채널 값. |
| [CustResource](./custresource/) | CustResource 클래스. 이 리소스는 클리핑된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [ExpaResource](./exparesource/) | 클래스 ExpaResource. 노출 조정 레이어의 리소스 |
| [FillLayerResource](./filllayerresource/) | 채우기 레이어 리소스의 기본 클래스. |
| [FilterEffectMaskData](./filtereffectmaskdata/) | 필터 마스크 데이터 클래스. |
| [FXidResource](./fxidresource/) | 필터 효과 리소스에는 채널, 사용자 마스크 및 스마트 필터용 시트 마스크가 포함됩니다. |
| [FxrpResource](./fxrpresource/) | 클래스 FxrpResource. 레이어의 기준점 |
| [GdFlResource](./gdflresource/) | 클래스 GdFlResource. 이 리소스는 클리핑된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [GrdmResource](./grdmresource/) | 클래스 GrdmResource. 그라디언트 맵 레이어에 대한 정보를 포함합니다. |
| [Hue2Resource](./hue2resource/) | 클래스 Hue2Resource. 노출 조정 레이어의 리소스 |
| [IfxsResource](./ifxsresource/) | Ifxs 리소스 (그룹 레이어 효과 리소스) |
| [ImfxResource](./imfxresource/) | Imfx 리소스 (멀티 효과 리소스) |
| [InfxResource](./infxresource/) | 클래스 InfxResource. 이 리소스는 클리핑된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [IopaResource](./ioparesource/) | 클래스 IopaResource. 이 리소스는 레이어 스타일 폼에서 채우기 불투명도 속성에 대한 정보를 포함합니다. |
| [KnkoResource](./knkoresource/) | 클래스 KnkoResource. 이 리소스는 클리핑된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [LayerSectionResource](./layersectionresource/) | 레이어 섹션 리소스. |
| [LclrResource](./lclrresource/) | 클래스 LclrResource. 이 리소스는 레이어 목록에 있는 레이어 색상에 대한 정보를 포함합니다. PS 전용입니다. |
| [LevelChannel](./levelchannel/) | 레벨 조정 레이어에서 채널을 작업하기 위한 클래스 |
| [LevlResource](./levlresource/) | 클래스 LevlResource. 노출 조정 레이어의 리소스 |
| [Lfx2Resource](./lfx2resource/) | Lfx2 리소스 (일반 효과 리소스) |
| [LiFdDataSource](./lifddatasource/) | PSD 파일에서 임베디드 파일에 대한 정보를 포함하는 liFD 데이터 소스 클래스를 정의합니다. 이는 Adobe® Photoshop® 파일을 수정하는 데 도움이 되는 PSD 파일 포맷 조작 API의 일부입니다. |
| [LiFeDataSource](./lifedatasource/) | 외부 링크 파일에 대한 정보를 포함하는 LnkeDataSource 클래스를 정의합니다. 이는 Adobe® Photoshop® 파일을 수정하는 데 도움이 되는 PSD 파일 포맷 조작 API의 일부입니다. |
| [LinkDataSource](./linkdatasource/) | PSD 파일에서 링크된 파일 또는 자산에 대한 정보를 포함하는 LinkDataSource 클래스를 정의합니다. |
| [LinkResource](./linkresource/) | PSD 포맷 이미지에서 링크되거나 임베디드된 파일에 대한 정보를 포함하는 LinkResource 클래스를 정의합니다. 링크 리소스는 여러 [`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) 인스턴스를 포함할 수 있으며, 이는 파생 클래스의 인덱서로 접근할 수 있습니다. |
| [LmskResource](./lmskresource/) | LMsk 리소스. |
| [Lnk2Resource](./lnk2resource/) | PSD 포맷 이미지에서 임베디드 파일에 대한 정보를 포함하는 클래스를 정의합니다. 링크 리소스는 여러 [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 인스턴스를 포함할 수 있으며, 이는 인덱서를 통해 접근할 수 있습니다. |
| [Lnk3Resource](./lnk3resource/) | PSD 포맷 32비트 채널 이미지에서 임베디드 파일에 대한 정보를 포함하는 클래스를 정의합니다. 링크 리소스는 여러 [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 인스턴스를 포함할 수 있으며, 이는 인덱서를 통해 접근할 수 있습니다. |
| [LnkeResource](./lnkeresource/) | LnkeResource 클래스를 정의하며, PSD 형식 이미지에서 외부 링크 파일 또는 자산에 대한 정보를 포함합니다. 링크 리소스는 인덱서를 통해 접근할 수 있는 여러 [`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 인스턴스를 포함할 수 있습니다. 이는 Adobe® Photoshop® 파일을 프로그래밍 방식으로 수정하는 데 도움이 되는 PSD 파일 형식 조작 API의 일부입니다. |
| [LnsrResource](./lnsrresource/) | lnsrResource 클래스. |
| [Lr16Resource](./lr16resource/) | lr16 리소스. |
| [Lr32Resource](./lr32resource/) | lr32 리소스. |
| [LrXxResource](./lrxxresource/) | lrXX 리소스. |
| [LsdkResource](./lsdkresource/) | lsdk 레이어 리소스(중첩 레이어 섹션 리소스). |
| [LspfResource](./lspfresource/) | 레이어 보호 설정 |
| [LuniResource](./luniresource/) | 레이어 이름 리소스 |
| [LyidResource](./lyidresource/) | LyidResource 클래스. |
| [LyvrResource](./lyvrresource/) | 레이어의 Photoshop 버전을 나타내는 리소스. |
| [MixrResource](./mixrresource/) | MixrResource 클래스. 채널 믹서 조정 레이어의 리소스 |
| [MlstResource](./mlstresource/) | mlst 리소스. 이 클래스는 기타 항목 중 레이어가 타임라인에 위치하는 정보 등을 포함합니다. |
| [NvrtResource](./nvrtresource/) | NvrtResource 클래스. 인버트 조정 레이어의 리소스. |
| [OSTypeStructure](./ostypestructure/) | OS 타입 구조를 나타냅니다. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 리소스 레지스트리를 나타냅니다. |
| [PathShape](./pathshape/) | 베지어 곡선 매듭에서 얻은 도형. |
| [PattResource](./pattresource/) | PattResource 클래스. 패턴 데이터를 포함하는 리소스 |
| [PattResourceData](./pattresourcedata/) | [`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 리소스의 패턴 데이터를 저장하는 클래스. |
| [PhflResource](./phflresource/) | PhflResource 클래스. 노출 조정 레이어 2 리소스. 버전( = 3) 또는 ( = 2) 12: 버전 3에서는 XYZ 색상당 4바이트, 10: 버전 2에서는 색상 공간 2바이트에 이어 4 * 2바이트 색상 구성 요소, 4: 밀도, 1: 밝기 보존. |
| [PhflResourceVersion2](./phflresourceversion2/) | PhflResource 클래스. 노출 조정 레이어 2 리소스. 버전( = 3) 또는 ( = 2) 12: 버전 3에서는 XYZ 색상당 4바이트, 10: 버전 2에서는 색상 공간 2바이트에 이어 4 * 2바이트 색상 구성 요소, 4: 밀도, 1: 밝기 보존. |
| [PhflResourceVersion3](./phflresourceversion3/) | PhflResource 클래스. 노출 조정 레이어 2 리소스. 버전( = 3) 또는 ( = 2) 12: 버전 3에서는 XYZ 색상당 4바이트, 10: 버전 2에서는 색상 공간 2바이트에 이어 4 * 2바이트 색상 구성 요소, 4: 밀도, 1: 밝기 보존. |
| [PlacedResource](./placedresource/) | PlacedResource 클래스를 정의하며, PSD 파일에서 배치 레이어 또는 스마트 오브젝트 레이어에 대한 일반 정보를 포함합니다. 이는 Adobe® Photoshop® 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다. |
| [PlLdResource](./plldresource/) | PlLdResource 클래스를 정의하며, PSD 파일에서 배치 레이어에 대한 정보를 포함합니다. 이는 Adobe® Photoshop® 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다. Adobe® Photoshop® CS3에서 SoLdResource로 대체되었습니다. |
| [PostResource](./postresource/) | PostResource 클래스. 포스터화 레이어 설정. |
| [PtFlResource](./ptflresource/) | PtFlResource 클래스. 패턴 채우기 레이어 데이터를 포함합니다. |
| [ShmdResource](./shmdresource/) | ShmdResource 클래스. 메타데이터 설정 |
| [SmartObjectResource](./smartobjectresource/) | SmartObjectResource 클래스를 정의하며, PSD 파일에서 스마트 오브젝트 레이어에 대한 정보를 포함합니다. 이는 Adobe® Photoshop® 이미지에서 스마트 오브젝트 레이어를 지원하는 Sold 및 Sole 리소스의 기본 클래스입니다. |
| [SmartResourceCreator](./smartresourcecreator/) | SmartResourceCreator 클래스를 정의하며 PlLd, SoLd 및 SoLe 리소스를 생성할 수 있습니다. Adobe® Photoshop® 이미지에서 스마트 객체 레이어를 지원하는 데 사용됩니다. |
| [SoCoResource](./socoresource/) | SoCoResource 클래스. 이 리소스는 색 채우기 레이어에 대한 정보를 포함합니다. |
| [SoLdResource](./soldresource/) | SoLdResource 클래스를 정의하며 PSD 파일의 스마트 객체 레이어에 대한 정보를 포함합니다. Adobe� Photoshop� 이미지에서 스마트 객체 레이어를 지원하는 데 사용됩니다. |
| [SoLeResource](./soleresource/) | SoLeResource 클래스를 정의하며 PSD 파일의 스마트 객체 레이어에 대한 정보를 포함합니다. 외부 파일 링크가 있는 스마트 객체 레이어를 Adobe� Photoshop� 이미지에서 지원하는 데 사용됩니다. |
| [Txt2Resource](./txt2resource/) | Txt2 리소스 클래스 |
| [TypeToolFontInfo](./typetoolfontinfo/) | 타입 도구 폰트에 대한 정보를 포함합니다. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | 타입 도구 정보. PSD 버전이 6.0 이상인 경우. |
| [TypeToolInfoResource](./typetoolinforesource/) | 타입 도구 정보. PSD 버전이 6.0 미만인 경우. |
| [TypeToolLineInfo](./typetoollineinfo/) | 타입 도구 라인 정보. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | 타입 도구 스타일 정보. |
| [UnknownResource](./unknownresource/) | 알 수 없는 리소스. |
| [VectorPath](./vectorpath/) | 벡터 경로를 포함하는 클래스. |
| [VectorPathDataResource](./vectorpathdataresource/) | VectorPathDataResource 클래스. 이 리소스는 벡터 레이어 마스크에 대한 정보를 포함합니다. |
| [VibAResource](./vibaresource/) | VibA 리소스. |
| [VmskResource](./vmskresource/) | VmskResource 클래스. 이 리소스는 벡터 레이어 마스크에 대한 정보를 포함합니다. |
| [VogkResource](./vogkresource/) | Vector Origination Data 리소스. |
| [VsmsResource](./vsmsresource/) | VsmsResource 클래스. 이 리소스는 벡터 레이어 마스크에 대한 정보를 포함합니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | 해당 [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 리소스 로더. |
| [IPath](./ipath/) | 인터페이스는 Shape 레이어에 존재하는 Path 집합을 설명합니다. |
| [IPathShape](./ipathshape/) | 베지어 곡선의 노드에서 만든 Shape. |
| [IPlacedLayerResource](./iplacedlayerresource/) | IPlacedLayerResource 인터페이스를 정의하며 PSD 파일의 배치된 레이어에 대한 정보를 포함합니다. Adobe® Photoshop® 이미지에서 PlLd, Sold 및 Sole 리소스를 지정하는 마크업 인터페이스이며, Adobe® Photoshop® 이미지에서 스마트 객체 레이어를 지원하는 데 사용됩니다. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | ISmartObjectLayerResource 인터페이스를 정의하며 PSD 파일의 스마트 객체 레이어 리소스에 대한 정보를 포함합니다. 또한 Adobe® Photoshop® 이미지에서 Sold 및 Sole 리소스를 지정하는 마크업 인터페이스입니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [LayerLockType](./layerlocktype/) | 레이어 잠금 옵션 |
| [LayerSectionSubtype](./layersectionsubtype/) | 섹션 하위 유형 |
| [LayerSectionType](./layersectiontype/) | 레이어 섹션 유형 |
| [LinkDataSourceType](./linkdatasourcetype/) | PSD 링크 리소스의 데이터 소스를 위한 LinkDataSourceType 열거형을 정의합니다. |
| [LnsrResourceType](./lnsrresourcetype/) | 가능한 Lnsr 리소스 유형을 발견했습니다. |
| [PlacedLayerType](./placedlayertype/) | 배치된 레이어 PlLd 리소스를 위한 PlacedLayerType 열거형을 정의합니다. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | 시트 색상 설정의 가능한 색상입니다. PS 레이어 목록에서 레이어의 UI 장식 색상입니다. |


