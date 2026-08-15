---
title: "GaussWienerFilterOptions 클래스"
type: docs
weight: 60
url: /ko/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | 새 인스턴스를 초기화합니다 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 클래스.<br/>            기본 설정으로. |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | 새 인스턴스를 초기화합니다 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 밝기 | double | r/w | 밝기를 가져오거나 설정합니다.<br/>            권장 범위 1 - 1.5<br/>            기본값 = 1.15 |
| grayscale | bool | r/w | 이 [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/)가 그레이스케일인지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            그레이스케일 모드 또는 RGB 모드를 반환합니다. |
| is_partial_loaded | bool | r | 이 인스턴스가 부분 로드되었는지 여부를 나타내는 값을 가져옵니다. |
| 반경 | int | r/w | 반경을 가져오거나 설정합니다. |
| 부드러움 | double | r/w | 부드러움을 가져오거나 설정합니다. |
| snr | double | r/w | SNR(신호 대 잡음 비율)을 가져오거나 설정합니다.<br/>            권장 범위 0.002 - 0.009, 기본값 = 0.007 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

새 인스턴스를 초기화합니다 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 클래스.<br/>            기본 설정으로.

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

새 인스턴스를 초기화합니다 [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 반경 | int | 반경. |
| 부드러움 | double | 부드러움. |

