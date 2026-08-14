---
title: "Classe TiffDataType"
type: docs
weight: 10
url: /it/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Restituisce la dimensione aggiuntiva dei dati in byte (nel caso in cui i 12 byte non siano sufficienti per contenere i dati del tag). |
| conteggio | uint | r | Restituisce il conteggio degli elementi. |
| data_size | uint | r | Restituisce la dimensione aggiuntiva dei dati in byte (nel caso in cui i 12 byte non siano sufficienti per contenere i dati del tag). |
| id | ushort | r | Restituisce la rappresentazione intera dell'ID del tag. |
| is_valid | bool | r | Restituisce un valore che indica se i dati del tag sono validi. Il tag valido contiene dati che possono essere conservati. Il tag non valido non può essere memorizzato. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Restituisce l'ID del tag. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Restituisce il tipo del tag. |
| value | object | r/w | Ottiene o imposta il valore contenuto da questo tipo di dati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento dell'altro oggetto. |
| [deep_clone()](#deep_clone__2) | Esegue una clonazione profonda di questa istanza. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Legge i dati del tag. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Scrive i dati aggiuntivi del tag. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Scrive i dati del tag. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Confronta l'istanza corrente con un altro oggetto dello stesso tipo e restituisce un intero che indica se l'istanza corrente precede, segue o si trova nella stessa posizione nell'ordine di ordinamento dell'altro oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| obj | object | Un oggetto da confrontare con questa istanza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un intero con segno a 32 bit che indica l'ordine relativo degli oggetti confrontati. Il valore restituito ha i seguenti significati:<br/>            Valore<br/>            Significato<br/>            Meno di zero<br/>            Questa istanza è minore di <paramref name="obj" />.<br/>            Zero<br/>            Questa istanza è uguale a <paramref name="obj" />.<br/>            Maggiore di zero<br/>            Questa istanza è maggiore di <paramref name="obj" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Esegue una clonazione profonda di questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Una copia profonda dell'istanza corrente. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Legge i dati del tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Il flusso di dati. |
| position | long | La posizione del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Il tag letto. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Scrive i dati aggiuntivi del tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Il flusso di dati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| long | Il numero effettivo di byte scritti. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Scrive i dati del tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Il flusso di dati. |
| additional_data_offset | long | L'offset a cui scrivere dati aggiuntivi. |

