---
title: "GdFlResource 클래스"
type: docs
weight: 330
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | GdFlResource 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 전용 리소스 서명입니다. |
| RESOURCE_SIGNATURE [static] | int | r | 공통 리소스 서명입니다. |
| TYPE_TOOL_KEY [static] | int | r | 타입 도구 정보 키입니다. |
| align_with_layer | bool | r/w | 값을 가져오거나 설정합니다. [align with layer] 여부를 나타냅니다. |
| 각도 | double | r/w | 각도를 가져오거나 설정합니다. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | RGB의 색상을 가져옵니다. |
| color_model | 문자열 | r/w | 색상 모델 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | 색상 포인트를 가져옵니다. |
| dither | bool | r/w | 이 [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| gradient_interval | double | r/w | 그라디언트 간격을 가져오거나 설정합니다. |
| gradient_mode | 문자열 | r/w | 이 그라디언트의 모드입니다.<br/>            'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs"를 결정합니다. |
| gradient_name | 문자열 | r/w | 그라디언트 이름을 가져오거나 설정합니다. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | 그라디언트 유형을 가져오거나 설정합니다. |
| horizontal_offset | double | r/w | 수평 오프셋을 가져오거나 설정합니다. |
| 키 | int | r | 레이어 리소스 키를 가져옵니다. |
| 길이 | int | r | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat의 최대 색상. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat의 최소 색상. |
| psd_version | int | r | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| reverse | bool | r/w | 이 [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| rnd_number_seed | int | r/w | 노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드입니다. |
| roughness | int | r/w | 거칠기 계수. |
| scale | int | r/w | scale을 가져오거나 설정합니다. |
| show_transparency | bool | r/w | 투명도를 표시하기 위한 플래그. |
| signature | int | r | 서명을 가져옵니다. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | 투명도 포인트를 가져옵니다. |
| use_vector_color | bool | r/w | 벡터 색상을 사용하기 위한 플래그. |
| vertical_offset | double | r/w | 수직 오프셋을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

GdFlResource 클래스의 새 인스턴스를 초기화합니다

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

리소스를 지정된 스트림 컨테이너에 저장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psd_version | int | PSD 버전. |

