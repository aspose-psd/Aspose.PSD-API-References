---
title: "MotionWienerFilterOptions 클래스"
type: docs
weight: 90
url: /ko/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** Deconvolution filter options<br/>                deblur motion

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [MotionWienerFilterOptions(length, smooth, angle)](#MotionWienerFilterOptions_length_smooth_angle_1) | 새 인스턴스를 초기화합니다 [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 각도 | double | r/w | 각도를 그라두스 단위로 가져오거나 설정합니다. |
| 밝기 | double | r/w | 밝기를 가져오거나 설정합니다.<br/>            권장 범위 1 - 1.5<br/>            기본값 = 1.15 |
| grayscale | bool | r/w | 이 [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/)가 그레이스케일인지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            그레이스케일 모드 또는 RGB 모드를 반환합니다. |
| is_partial_loaded | bool | r | 이 인스턴스가 부분 로드되었는지 여부를 나타내는 값을 가져옵니다. |
| 길이 | int | r/w | 길이를 가져오거나 설정합니다. |
| 부드러움 | double | r/w | 부드러움을 가져오거나 설정합니다. |
| snr | double | r/w | SNR(신호 대 잡음 비율)을 가져오거나 설정합니다.<br/>            권장 범위 0.002 - 0.009, 기본값 = 0.007 |


### Constructor: MotionWienerFilterOptions(length, smooth, angle) {#MotionWienerFilterOptions_length_smooth_angle_1}


```
 MotionWienerFilterOptions(length, smooth, angle) 
```

새 인스턴스를 초기화합니다 [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 길이 | int | 길이. |
| 부드러움 | double | 부드러움. |
| 각도 | double | 그라두스 단위의 각도. |

