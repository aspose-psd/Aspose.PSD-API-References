---
title: "Clase PsdLoadOptions"
type: docs
weight: 30
url: /es/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Inicializa una nueva instancia de la clase PsdLoadOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Obtiene o establece si guardar con la imagen renderizada, con o sin una transformación warp. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color de fondo de la [Image](/psd/python-net/aspose.psd/image/) [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Obtiene o establece el modo de recuperación de datos. |
| ignore_alpha_channel | bool | r/w | Obtiene o establece un valor que indica si [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Obtiene o establece un valor que indica si el ancho fijo de la capa de texto PSD será ignorado durante la ejecución de la operación UpdateText. |
| load_effects_resource | bool | r/w | Obtiene o establece un valor que indica si [load effects resource] (por defecto el recurso no está cargado). Cuando se establece esta opción, solo los efectos compatibles se renderizarán en la imagen final combinada. |
| read_only_mode | bool | r/w | Obtiene o establece un valor que indica si [use read only mode]. Este es el modo de solo lectura, compatible para una compatibilidad idéntica con Adobe Photoshop.<br/>            Cuando esta opción está establecida, todos los cambios aplicados a las capas no se guardarán en la imagen final. Todos los datos se utilizan de la sección ImageData, por lo que es idéntico a Photoshop. <br/>            Por defecto, todas las imágenes cargadas no son idénticas a la compatibilidad de Adobe Photoshop. |
| use_disk_for_load_effects_resource | bool | r/w | Obtiene o establece un valor que indica si [use disk for load effects resource] (por defecto se usa disco para cargar el recurso de efectos, pero se puede usar memoria si es suficiente al establecer este valor en false). |
| use_icc_profile_conversion | bool | r/w | Obtiene o establece un valor que indica si se debe aplicar la conversión de perfil ICC. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Inicializa una nueva instancia de la clase PsdLoadOptions

