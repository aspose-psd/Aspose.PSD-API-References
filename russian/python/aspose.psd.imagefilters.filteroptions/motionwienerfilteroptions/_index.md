---
title: "Класс MotionWienerFilterOptions"
type: docs
weight: 90
url: /ru/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Summary:** Deconvolution filter options<br/>                deblur motion

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [MotionWienerFilterOptions(length, smooth, angle)](#MotionWienerFilterOptions_length_smooth_angle_1) | Инициализирует новый экземпляр класса [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| угол | double | r/w | Получает или задает угол в градусах. |
| яркость | double | r/w | Получает или задает яркость.<br/>рекомендуемый диапазон 1 - 1.5<br/>значение по умолчанию = 1.15 |
| grayscale | bool | r/w | Получает или задает значение, указывающее, является ли этот [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) в градациях серого.<br/>Возвращает режим градаций серого или режим RGB. |
| is_partial_loaded | bool | r | Получает значение, указывающее, загружен ли этот экземпляр частично. |
| длина | int | r/w | Получает или задает длину. |
| сглаживание | double | r/w | Получает или задает сглаживание. |
| snr | double | r/w | Получает или задает SNR (отношение сигнал/шум)<br/>рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007 |


### Constructor: MotionWienerFilterOptions(length, smooth, angle) {#MotionWienerFilterOptions_length_smooth_angle_1}


```
 MotionWienerFilterOptions(length, smooth, angle) 
```

Инициализирует новый экземпляр класса [MotionWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| длина | int | Длина. |
| сглаживание | double | Сглаживание. |
| угол | double | Угол в градусах. |

