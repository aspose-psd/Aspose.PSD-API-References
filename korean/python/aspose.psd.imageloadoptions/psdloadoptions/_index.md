---
title: "PsdLoadOptions 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | 새 인스턴스를 초기화합니다 PsdLoadOptions 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | 렌더링된 이미지와 함께 저장할지 여부를 가져오거나 설정합니다(워프 변환 포함 여부). |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 가져오거나 설정합니다 [Image](/psd/python-net/aspose.psd/image/) 배경 [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | 데이터 복구 모드를 가져오거나 설정합니다. |
| ignore_alpha_channel | bool | r/w | 값을 가져오거나 설정하며, [ignore alpha channel]인지 여부를 나타냅니다. |
| ignore_text_layer_width_on_update | bool | r/w | 값을 가져오거나 설정하며, UpdateText 작업 실행 시 PSD 텍스트 레이어 고정 너비가 무시되는지 여부를 나타냅니다. |
| load_effects_resource | bool | r/w | 값을 가져오거나 설정하며, [load effects resource]인지 여부를 나타냅니다(기본적으로 리소스가 로드되지 않음). 이 옵션을 설정하면 지원되는 효과만 최종 병합 이미지에 렌더링됩니다. |
| read_only_mode | bool | r/w | 값을 가져오거나 설정하며, [use read only mode]인지 여부를 나타냅니다. 이는 Adobe Photoshop과 동일한 호환성을 위해 지원되는 읽기 전용 모드입니다.<br/>            이 옵션을 설정하면 레이어에 적용된 모든 변경 사항이 최종 이미지에 저장되지 않습니다. 모든 데이터는 ImageData 섹션에서 사용되므로 Photoshop과 동일합니다. <br/>            기본적으로 모든 로드된 이미지는 Adobe Photoshop 호환과 동일하지 않습니다. |
| use_disk_for_load_effects_resource | bool | r/w | 값을 가져오거나 설정하며, [use disk for load effects resource]인지 여부를 나타냅니다(기본적으로 효과 리소스를 로드하기 위해 디스크를 사용하지만, 이 값을 false로 설정하면 메모리를 사용할 수 있습니다). |
| use_icc_profile_conversion | bool | r/w | ICC 프로파일 변환을 적용할지 여부를 나타내는 값을 가져오거나 설정합니다. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

새 인스턴스를 초기화합니다 PsdLoadOptions 클래스.

