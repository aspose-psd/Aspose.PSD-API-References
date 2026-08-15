---
title: "Класс PsdLoadOptions"
type: docs
weight: 30
url: /ru/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Инициализирует новый экземпляр класса PsdLoadOptions. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Получает или задаёт, сохранять ли с отрисованным изображением, с трансформацией warp или без неё. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задаёт фон изображения [Image](/psd/python-net/aspose.psd/image/) и [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Получает или задаёт режим восстановления данных. |
| ignore_alpha_channel | bool | r/w | Получает или задает значение, указывающее, следует ли [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Получает или задает значение, указывающее, будет ли фиксированная ширина текстового слоя PSD игнорироваться при выполнении операции UpdateText. |
| load_effects_resource | bool | r/w | Получает или задает значение, указывающее, следует ли [load effects resource] (по умолчанию ресурс не загружается). При включении этой опции будут отрисованы только поддерживаемые эффекты в итоговое объединённое изображение. |
| read_only_mode | bool | r/w | Получает или задает значение, указывающее, следует ли [use read only mode]. Это режим только для чтения, поддерживаемый для полной совместимости с Adobe Photoshop.<br/>            Когда эта опция включена, все изменения, применённые к слоям, не сохраняются в итоговое изображение. Все данные берутся из раздела ImageData, поэтому они идентичны Photoshop.<br/>            По умолчанию все загруженные изображения не полностью совместимы с Adobe Photoshop. |
| use_disk_for_load_effects_resource | bool | r/w | Получает или задает значение, указывающее, следует ли [use disk for load effects resource] (по умолчанию используется диск для загрузки ресурсов эффектов, но при установке этого значения в false может использоваться память, если её достаточно). |
| use_icc_profile_conversion | bool | r/w | Получает или задаёт значение, указывающее, следует ли применять преобразование ICC‑профиля. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Инициализирует новый экземпляр класса PsdLoadOptions.

