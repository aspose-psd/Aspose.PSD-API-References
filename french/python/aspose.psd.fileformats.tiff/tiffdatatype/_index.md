---
title: "Classe TiffDataType"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Obtient la taille supplémentaire des données en octets (dans le cas où les 12 octets ne suffisent pas à contenir les données de l'étiquette). |
| count | uint | r | Obtient le nombre d'éléments. |
| data_size | uint | r | Obtient la taille supplémentaire des données en octets (dans le cas où les 12 octets ne suffisent pas à contenir les données de l'étiquette). |
| id | ushort | r | Obtient la représentation entière de l'identifiant de l'étiquette. |
| is_valid | bool | r | Obtient une valeur indiquant si les données de l'étiquette sont valides. L'étiquette valide contient des données qui peuvent être conservées. L'étiquette invalide ne peut pas être stockée. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Obtient l'identifiant de l'étiquette. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Obtient le type de l'étiquette. |
| valeur | object | r/w | Obtient ou définit la valeur que ce type de données contient. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier indiquant si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet. |
| [deep_clone()](#deep_clone__2) | Effectue un clonage profond de cette instance. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Lit les données de l'étiquette. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Écrit les données supplémentaires de l'étiquette. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Écrit les données de la balise. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Compare l'instance actuelle avec un autre objet du même type et renvoie un entier indiquant si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| obj | object | Un objet à comparer avec cette instance. |

**Returns**

| Type | Description |
| :- | :- |
| int | Un entier signé de 32 bits qui indique l'ordre relatif des objets comparés. La valeur de retour a les significations suivantes:<br/>            Valeur<br/>            Signification<br/>            Inférieur à zéro<br/>            Cette instance est inférieure à <paramref name="obj" />.<br/>            Zéro<br/>            Cette instance est égale à <paramref name="obj" />.<br/>            Supérieur à zéro<br/>            Cette instance est supérieure à <paramref name="obj" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Effectue un clonage profond de cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Une copie profonde de l'instance actuelle. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Lit les données de l'étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Le flux de données. |
| position | long | La position de la balise. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | La balise lue. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Écrit les données supplémentaires de l'étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Le flux de données. |

**Returns**

| Type | Description |
| :- | :- |
| long | Les octets réellement écrits. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Écrit les données de la balise.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Le flux de données. |
| additional_data_offset | long | Le décalage où écrire les données supplémentaires. |

