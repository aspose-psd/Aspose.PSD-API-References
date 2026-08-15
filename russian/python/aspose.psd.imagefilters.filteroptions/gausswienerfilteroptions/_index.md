---
title: "Класс GaussWienerFilterOptions"
type: docs
weight: 60
url: /ru/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Инициализирует новый экземпляр класса [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) .<br/>            С настройками по умолчанию. |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | Инициализирует новый экземпляр класса [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| яркость | double | r/w | Получает или задает яркость.<br/>рекомендуемый диапазон 1 - 1.5<br/>значение по умолчанию = 1.15 |
| grayscale | bool | r/w | Получает или задает значение, указывающее, является ли этот [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) в градациях серого.<br/>Возвращает режим градаций серого или режим RGB. |
| is_partial_loaded | bool | r | Получает значение, указывающее, загружен ли этот экземпляр частично. |
| радиус | int | r/w | Получает или задает радиус. |
| сглаживание | double | r/w | Получает или задает сглаживание. |
| snr | double | r/w | Получает или задает SNR (отношение сигнал/шум)<br/>рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Инициализирует новый экземпляр класса [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) .<br/>            С настройками по умолчанию.

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

Инициализирует новый экземпляр класса [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| радиус | int | Радиус. |
| сглаживание | double | Сглаживание. |

