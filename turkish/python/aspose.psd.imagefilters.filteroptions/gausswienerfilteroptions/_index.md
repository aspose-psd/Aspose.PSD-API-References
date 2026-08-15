---
title: "GaussWienerFilterOptions Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Yeni bir [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) sınıfının örneğini başlatır.<br/>            Varsayılan ayarlarla. |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | Yeni bir [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| parlaklık | double | r/w | Parlaklığı alır veya ayarlar.<br/>            önerilen aralık 1 - 1.5<br/>            varsayılan değer = 1.15 |
| grayscale | bool | r/w | Bu [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) öğesinin gri tonlamalı olup olmadığını belirten bir değeri alır veya ayarlar.<br/>            Gri tonlama modu veya RGB modunu döndürür. |
| is_partial_loaded | bool | r | Bu örneğin kısmen yüklendiğini belirten bir değeri alır. |
| yarıçap | int | r/w | Yarıçapı alır veya ayarlar. |
| yumuşaklık | double | r/w | Yumuşaklığı alır veya ayarlar. |
| snr | double | r/w | SNR (signal-to-noise ratio) değerini alır veya ayarlar.<br/>            önerilen aralık 0.002 - 0.009, varsayılan değer = 0.007 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Yeni bir [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) sınıfının örneğini başlatır.<br/>            Varsayılan ayarlarla.

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

Yeni bir [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yarıçap | int | Yarıçap. |
| yumuşaklık | double | Yumuşaklık. |

