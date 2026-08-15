---
title: "Clase Timeline"
type: docs
weight: 40
url: /es/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Timeline()](#Timeline__1) | Inicializa una nueva instancia de la clase Timeline |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Obtiene el índice del fotograma activo. |
| af_st | int | r/w | Obtiene o establece el valor de AFSt. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Obtiene la lista de fotogramas. |
| fs_id | int | r/w | Obtiene o establece el valor de FsID. |
| loopes_count | ushort | r/w | Obtiene o establece el recuento de bucles. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Guarda los datos de PsdImage y Timeline en la ubicación de archivo especificada en el formato especificado según las opciones de guardado. |
| [save(output_stream, options)](#save_output_stream_options_2) | Guarda los datos de PsdImage y Timeline en el flujo especificado en el formato especificado según las opciones de guardado. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Cambia el fotograma activo al objetivo. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Inicializa una nueva instancia de la clase Timeline

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Guarda los datos de PsdImage y Timeline en la ubicación de archivo especificada en el formato especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Guarda los datos de PsdImage y Timeline en el flujo especificado en el formato especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | El flujo de salida. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Cambia el fotograma activo al objetivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_active_frame_index | int | El índice del fotograma objetivo. |

