---
title: "GrdmResource 클래스"
type: docs
weight: 340
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| color_model | short | r/w | 색상 모델.<br/>            'Gradient type' = 'Noise'인 경우, 'Color Model'을 RGB/SHB/LAB (3/4/6)으로 지정할 수 있습니다. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | 색상 포인트를 가져오거나 설정합니다. |
| dither | bool | r/w | 그라디언트가 디더링되었는지 여부. |
| expansion_count | short | r/w | 확장 카운트 ( = Photoshop 6.0의 경우 2). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | 이 그라디언트의 모드<br/>            'Gradient Type' = 'Solid/Noise' (0/1)를 결정합니다. |
| gradient_name | 문자열 | r/w | 그라디언트 이름: 유니코드 문자열, 패딩됨. |
| 보간 | short | r/w | 보간. 'Gradient Type' = 'Solid' (GradientMode = 0)일 때 부드러움을 결정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp 형식의 최대 색상.<br/>            색상은 ARGB 채널을 가지며, 각 채널은 16비트입니다. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp 형식의 최소 색상.<br/>            색상은 ARGB 채널을 가지며, 각 채널은 16비트입니다. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| 역방향 | bool | r/w | 그라디언트가 역방향인지 여부. |
| rnd_number_seed | int | r/w | 노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드입니다. |
| roughness | int | r/w | 거칠기 계수<br/>            'Gradient type' = 'Noise'인 경우, 'Roughness' (0 - 2048)를 지정할 수 있습니다. |
| show_transparency | short | r/w | 투명도 표시 플래그<br/>            'Gradient type' = 'Noise'인 경우, 'Add transparency'를 true로 지정할 수 있습니다. |
| signature | int | r | 서명을 가져옵니다. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | 투명도 포인트를 가져오거나 설정합니다. |
| use_vector_color | short | r/w | 벡터 색상을 사용하기 위한 플래그. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스 데이터를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

[GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| psd_version | int | 리소스의 psd 버전. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

리소스 데이터를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| psd_version | int | PSD 버전. |

