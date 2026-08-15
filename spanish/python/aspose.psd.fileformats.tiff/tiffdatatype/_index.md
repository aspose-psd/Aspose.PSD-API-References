---
title: "Clase TiffDataType"
type: docs
weight: 10
url: /es/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Obtiene el tamaño adicional de datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta). |
| count | uint | r | Obtiene la cantidad de elementos. |
| data_size | uint | r | Obtiene el tamaño adicional de datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta). |
| id | ushort | r | Obtiene la representación entera del id de la etiqueta. |
| is_valid | bool | r | Obtiene un valor que indica si los datos de la etiqueta son válidos. La etiqueta válida contiene datos que pueden preservarse. La etiqueta inválida no puede almacenarse. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Obtiene el id de la etiqueta. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Obtiene el tipo de etiqueta. |
| value | object | r/w | Obtiene o establece el valor que contiene este tipo de datos. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [deep_clone()](#deep_clone__2) | Realiza una clonación profunda de esta instancia. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Lee los datos de la etiqueta. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Escribe los datos adicionales de la etiqueta. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Escribe los datos de la etiqueta. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| obj | object | Un objeto para comparar con esta instancia. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Un entero con signo de 32 bits que indica el orden relativo de los objetos que se comparan. El valor de retorno tiene estos significados:<br/>            Valor<br/>            Significado<br/>            Menor que cero<br/>            Esta instancia es menor que <paramref name=\"obj\" />.<br/>            Cero<br/>            Esta instancia es igual a <paramref name=\"obj\" />.<br/>            Mayor que cero<br/>            Esta instancia es mayor que <paramref name=\"obj\" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Realiza una clonación profunda de esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Una copia profunda de la instancia actual. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Lee los datos de la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | El flujo de datos. |
| position | long | La posición de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | La etiqueta leída. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Escribe los datos adicionales de la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | El flujo de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| long | Los bytes reales escritos. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Escribe los datos de la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | El flujo de datos. |
| additional_data_offset | long | El desplazamiento donde escribir datos adicionales. |

