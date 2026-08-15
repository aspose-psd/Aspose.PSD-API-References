---
title: "aspose.psd.fileformats.psd.layers.layerresources"
type: docs
weight: 330
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/
---




## **Classes**
| **Class** | **설명** |
| :- | :- |
| [AbddResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/) | 아트보드 정보 데이터. |
| [AdjustmentLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/) | 조정 레이어 리소스를 위한 기본 클래스 |
| [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | 애니메이션 데이터가 포함된 섹션. |
| [ArtBResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) | 아트보드 정보 데이터: [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [ArtDResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/) | 아트보드 정보 데이터: [PsdImage.global_layer_resources](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [BaseArtboardInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/) | 아트보드 정보 데이터 리소스. |
| [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) | BlncResource 클래스는 색상 조정 레이어의 리소스입니다. |
| [BlwhResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/) | BlwhResource 클래스는 흑백 조정 레이어의 리소스입니다. |
| [BooleanResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/booleanresource/) | BooleanResource 클래스. 이것은 가상 리소스입니다. Photoshop에는 없습니다. |
| [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) | BritResource 클래스. 밝기/대비 조정 레이어의 리소스 |
| [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) | CgEdResource 클래스. 콘텐츠 생성기 추가 데이터 (Photoshop CS5) |
| [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid/) | PSD 클래스 ID 객체. |
| [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) | ClblResource 클래스.<br/>            이 리소스는 클리핑된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) | CmlsResource 클래스. |
| [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) | [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/)은 HSV 매개변수를 변경할 수 있는 6개의 색상 범위를 가지고 있습니다. <br/>            각 범위에는 범위 경계를 식별하기 위한 4개의 키 포인트가 있습니다. 그리고 이것은 ColorRangeHsl입니다. |
| [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) | CurvResource 클래스. 곡선 조정 레이어의 리소스<br/>            1 바이트 - 곡선을 사용하면 0, 맵에 픽셀을 사용하면 1<br/>            0인 경우:<br/>            2 바이트 - short. 기본값은 1<br/>            4 바이트 - int. 비트별로 마지막 바이트만 사용. 첫 번째 비트는 1채널, 네 번째 비트는 4채널 예시<br/>            2 바이트 - short 포인트 수<br/>            4 바이트 * 포인트 수 - 곡선 포인트 2 short: 첫 번째 위치, 두 번째 높이<br/>            4 바이트 - 단어 "Crv "<br/>            2 바이트 - short 기본값은 곡선의 경우 4<br/>            4 바이트 - int. 기본값은 1<br/>            4 바이트 - 포인트 수<br/>            4 바이트 * 포인트 수 - 곡선 포인트 2 short: 첫 번째 위치, 두 번째 높이<br/>            0-4 바이트 - 네 개를 위한 선행<br/>            1인 경우:<br/>            2 바이트 - short. 기본값은 1<br/>            4 바이트 - int. 마지막 바이트만 사용. 하나의 채널은 하나의 비트에. 첫 번째 비트는 1채널, 네 번째 비트는 4채널 예시<br/>            256 * 변경된 채널 수 - 0-255 범위의 정렬된 채널 값<br/>            4 바이트 - 단어 "Crv "<br/>            2 바이트 - short. 기본값은 맵의 픽셀 경우 3<br/>            4 바이트 - int 채널 수<br/>            (2 + 256) 바이트 - short 2는 채널 인덱스, 256은 0-255 범위의 정렬된 채널 값 |
| [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) | 곡선을 조작하는 곡선 조정 레이어용 매니저 |
| [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) | 픽셀 맵을 조작하는 곡선 조정 레이어 관리자 |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | CurvResource를 관리하기 위한 기본 클래스 |
| [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) | Class CustResource.<br/>            이 리소스는 클립된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) | Class ExpaResource. 노출 조정 레이어의 리소스 |
| [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) | 필터 효과 리소스에는 채널, 사용자 마스크 및 스마트 필터용 시트 마스크가 포함됩니다. |
| [FillLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filllayerresource/) | 채우기 레이어 리소스를 위한 기본 클래스. |
| [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) | 필터 마스크 데이터 클래스. |
| [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) | Class FxrpResource. 레이어의 기준점 |
| [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) | Class GdFlResource.<br/>            이 리소스는 클립된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) | Class GrdmResource. 그라디언트 맵 레이어에 대한 정보를 포함합니다. |
| [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) | Class Hue2Resource. 노출 조정 레이어의 리소스. |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/) | The [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 리소스 로더. |
| [IPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipath/) | 인터페이스는 Shape 레이어에 존재하는 경로 집합을 설명합니다. |
| [IPathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/) | 베지어 곡선의 노드에서 만든 Shape. |
| [IPlacedLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/) | PSD 파일에서 배치된 레이어에 대한 정보를 포함하는 IPlacedLayerResource 인터페이스를 정의합니다.<br/>            이는 Adobe® Photoshop® 이미지에서 PlLd, Sold 및 Sole 리소스를 지정하는 데 사용되는 마크업 인터페이스입니다.<br/>            이는 Adobe® Photoshop® 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다. |
| [ISmartObjectLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/) | PSD 파일에서 스마트 오브젝트 레이어 리소스에 대한 정보를 포함하는 ISmartObjectLayerResource 인터페이스를 정의합니다.<br/>            이는 Adobe® Photoshop® 이미지에서 Sold 및 Sole 리소스를 모두 지정하는 마크업 인터페이스이기도 합니다. |
| [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) | Class InfxResource.<br/>            이 리소스는 클립된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) | Class IopaResource.<br/>            이 리소스는 레이어 스타일 폼에서 채우기 불투명도 속성에 대한 정보를 포함합니다. |
| [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) | Class KnkoResource.<br/>            이 리소스는 클립된 요소의 블렌딩에 대한 정보를 포함합니다. |
| [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) | 레이어 섹션 리소스. |
| [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) | Class LclrResource.<br/>            이 리소스는 PS 레이어 목록에 있는 레이어 색상에 대한 정보를 포함합니다. 이것만 |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel/) | 레벨 조정 레이어에서 채널을 작업하기 위한 클래스 |
| [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) | Class LevlResource. 노출 조정 레이어의 리소스. |
| [Lfx2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/) | Lfx2 리소스 (효과 리소스) |
| [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) | PSD 파일에서 임베디드 파일에 대한 정보를 포함하는 liFD 데이터 소스 클래스를 정의합니다.<br/>            이는 Adobe® Photoshop® 파일을 수정하는 데 도움이 되는 PSD 파일 포맷 조작 API의 일부입니다. |
| [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) | 외부 링크된 파일에 대한 정보를 포함하는 LnkeDataSource 클래스를 정의합니다.<br/>            이는 Adobe® Photoshop® 파일을 수정하는 데 도움이 되는 PSD 파일 형식 조작 API의 일부입니다. |
| [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | PSD 파일에서 링크된 파일 또는 자산에 대한 정보를 포함하는 LinkDataSource 클래스를 정의합니다. |
| [LinkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/) | PSD 형식 이미지에서 링크되거나 포함된 파일에 대한 정보를 포함하는 LinkResource 클래스를 정의합니다.<br/>            링크 리소스는 여러 [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) 인스턴스를 포함할 수 있으며, 이는 파생 클래스의 인덱서로 접근할 수 있습니다. |
| [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) | LMsk 리소스. |
| [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) | PSD 형식 이미지에서 포함된 파일에 대한 정보를 포함하는 클래스를 정의합니다.<br/>            링크 리소스는 여러 [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 인스턴스를 포함할 수 있으며, 이는 인덱서를 통해 접근할 수 있습니다. |
| [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) | PSD 형식 32비트 채널 이미지에서 포함된 파일에 대한 정보를 포함하는 클래스를 정의합니다.<br/>            링크 리소스는 여러 [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) 인스턴스를 포함할 수 있으며, 이는 인덱서를 통해 접근할 수 있습니다. |
| [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) | PSD 형식 이미지에서 외부 링크된 파일 또는 자산에 대한 정보를 포함하는 LnkeResource 클래스를 정의합니다.<br/>            링크 리소스는 여러 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 인스턴스를 포함할 수 있으며, 이는 인덱서를 통해 접근할 수 있습니다.<br/>            이는 Adobe® Photoshop® 파일을 프로그래밍 방식으로 수정하는 데 도움이 되는 PSD 파일 형식 조작 API의 일부입니다. |
| [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) | lnsrResource 클래스. |
| [Lr16Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/) | lr16 리소스. |
| [Lr32Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/) | lr32 리소스. |
| [LrXxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/) | lrXX 리소스. |
| [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) | 레이어 보호 설정 |
| [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) | 레이어 이름 리소스 |
| [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) | LyidResource 클래스. |
| [LyvrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/) | 레이어의 Photoshop 버전을 나타내는 리소스. |
| [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) | MixrResource 클래스. 채널 믹서 조정 레이어의 리소스 |
| [MlstResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/) | mlst 리소스.<br/>            이 클래스는 기타 여러 기능 중 레이어가 타임라인에서 차지하는 위치에 대한 정보를 포함합니다. |
| [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) | NvrtResource 클래스. 반전 조정 레이어의 리소스. |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) | OS 유형 구조를 나타냅니다. |
| [OSTypeStructuresRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/) | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 리소스 레지스트리를 나타냅니다. |
| [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) | 베지어 곡선의 매듭에서 나온 도형. |
| [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) | PattResource 클래스. 패턴 데이터를 포함하는 리소스 |
| [PattResourceData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/) | [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) 리소스의 패턴 데이터를 저장하는 클래스. |
| [PhflResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/) | PhflResource 클래스. 노출 조정 레이어의 리소스<br/>            2 버전 ( = 3 ) 또는 ( = 2 )<br/>            12 각 XYZ 색상당 4바이트(버전 3에만 해당)<br/>            10 색상 공간 2바이트 뒤에 4 * 2바이트 색상 구성 요소(버전 2에만 해당)<br/>            4 밀도<br/>            1 밝기 보존 |
| [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) | PhflResource 클래스. 노출 조정 레이어의 리소스<br/>            2 버전 ( = 3 ) 또는 ( = 2 )<br/>            12 각 XYZ 색상당 4바이트(버전 3에만 해당)<br/>            10 색상 공간 2바이트 뒤에 4 * 2바이트 색상 구성 요소(버전 2에만 해당)<br/>            4 밀도<br/>            1 밝기 보존 |
| [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) | PhflResource 클래스. 노출 조정 레이어의 리소스<br/>            2 버전 ( = 3 ) 또는 ( = 2 )<br/>            12 각 XYZ 색상당 4바이트(버전 3에만 해당)<br/>            10 색상 공간 2바이트 뒤에 4 * 2바이트 색상 구성 요소(버전 2에만 해당)<br/>            4 밀도<br/>            1 밝기 보존 |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) | PSD 파일에서 배치된 레이어에 대한 정보를 포함하는 PlLdResource 클래스를 정의합니다.<br/>            이는 Adobe® Photoshop® 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다.<br/>            Adobe® Photoshop® CS3에서 SoLdResource로 대체되었습니다. |
| [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/) | PSD 파일에서 배치 레이어 또는 스마트 오브젝트 레이어에 대한 일반 정보를 포함하는 PlacedResource 클래스를 정의합니다.<br/>            Adobe Photoshop 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다. |
| [PostResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/) | Class PostResource. 포스터라이즈 레이어 설정. |
| [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) | Class PtFlResource. 패턴 채우기 레이어 데이터를 포함합니다. |
| [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) | Class ShmdResource. 메타데이터 설정 |
| [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) | PSD 파일에서 스마트 오브젝트 레이어에 대한 정보를 포함하는 SmartObjectResource 클래스를 정의합니다.<br/>            스마트 오브젝트 레이어를 지원하는 데 사용되는 Sold 및 Sole 리소스의 기본 클래스입니다. |
| [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) | PlLd, SoLd 및 SoLe 리소스를 생성할 수 있는 SmartResourceCreator 클래스를 정의합니다.<br/>            Adobe Photoshop 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다. |
| [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) | Class SoCoResource.<br/>            이 리소스는 컬러 채우기 레이어에 대한 정보를 포함합니다. |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) | PSD 파일에서 스마트 오브젝트 레이어에 대한 정보를 포함하는 SoLdResource 클래스를 정의합니다.<br/>            Adobe Photoshop 이미지에서 스마트 오브젝트 레이어를 지원하는 데 사용됩니다. |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) | PSD 파일에서 스마트 오브젝트 레이어에 대한 정보를 포함하는 SoLeResource 클래스를 정의합니다.<br/>            외부 파일 링크가 있는 스마트 오브젝트 레이어를 Adobe Photoshop 이미지에서 지원하는 데 사용됩니다. |
| [Txt2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/) | Txt2 리소스 클래스 |
| [TypeToolFontInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo/) | 타입 도구 글꼴에 대한 정보를 포함합니다. |
| [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) | 타입 도구 정보. PSD 버전 6.0 이상에 해당합니다. |
| [TypeToolInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/) | 타입 도구 정보. PSD 버전 6.0 미만에 해당합니다. |
| [TypeToolLineInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo/) | 타입 도구 라인 정보. |
| [TypeToolStyleInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo/) | 타입 도구 스타일 정보. |
| [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) | 알 수 없는 리소스. |
| [VectorPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/) | 벡터 경로를 포함하는 클래스. |
| [VectorPathDataResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/) | Class VectorPathDataResource.<br/>            이 리소스는 벡터 레이어 마스크에 대한 정보를 포함합니다. |
| [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) | VibA 리소스. |
| [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) | Class VmskResource.<br/>            이 리소스는 벡터 레이어 마스크에 대한 정보를 포함합니다. |
| [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) | 벡터 기원 데이터 리소스. |
| [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) | Class VsmsResource.<br/>            이 리소스는 벡터 레이어 마스크에 대한 정보를 포함합니다. |
## **Enumerations**
| **열거형** | **설명** |
| :- | :- |
| [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | 레이어 잠금 옵션 |
| [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype/) | 섹션 서브타입 |
| [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype/) | 레이어 섹션 유형 |
| [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype/) | PSD 링크 리소스의 데이터 소스를 위한 LinkDataSourceType 열거형을 정의합니다. |
| [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype/) | 가능한 Lnsr 리소스 유형을 발견했습니다. |
| [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype/) | 배치된 레이어 PlLd 리소스를 위한 PlacedLayerType 열거형을 정의합니다. |
| [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | 시트 색상 설정의 가능한 색상입니다.<br/>            이는 PS 레이어 목록에서 레이어의 UI 장식 색상입니다. |
