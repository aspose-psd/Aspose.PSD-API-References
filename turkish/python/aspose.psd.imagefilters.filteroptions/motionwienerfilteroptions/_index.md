---
title: "MotionWienerFilterOptions Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** Deconvolution filter options<br/>                deblur motion

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [MotionWienerFilterOptions(length, smooth, angle)](#MotionWienerFilterOptions_length_smooth_angle_1) | Yeni bir [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| açı | double | r/w | Açıyı gradus cinsinden alır veya ayarlar. |
| parlaklık | double | r/w | Parlaklığı alır veya ayarlar.<br/>            önerilen aralık 1 - 1.5<br/>            varsayılan değer = 1.15 |
| grayscale | bool | r/w | Bu [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) öğesinin gri tonlamalı olup olmadığını belirten bir değeri alır veya ayarlar.<br/>            Gri tonlama modu veya RGB modunu döndürür. |
| is_partial_loaded | bool | r | Bu örneğin kısmen yüklendiğini belirten bir değeri alır. |
| uzunluk | int | r/w | Uzunluğu alır veya ayarlar. |
| yumuşaklık | double | r/w | Yumuşaklığı alır veya ayarlar. |
| snr | double | r/w | SNR (signal-to-noise ratio) değerini alır veya ayarlar.<br/>            önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007 |


### Constructor: MotionWienerFilterOptions(length, smooth, angle) {#MotionWienerFilterOptions_length_smooth_angle_1}


```
 MotionWienerFilterOptions(length, smooth, angle) 
```

Yeni bir [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| uzunluk | int | Uzunluk. |
| yumuşaklık | double | Yumuşaklık. |
| açı | double | Gradus cinsinden açı. |

