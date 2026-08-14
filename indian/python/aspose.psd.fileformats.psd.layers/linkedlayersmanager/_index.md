---
title: "LinkedLayersManager क्लास"
type: docs
weight: 1140
url: /hi/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | लिंक समूह आईडी द्वारा लेयर्स प्राप्त करता है। |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | लेयर से जुड़े लिंक समूह आईडी को प्राप्त करता है। |
| [link_layers(layers)](#link_layers_layers_3) | इनपुट लेयर्स को लिंक करता है और LingGroupId लौटाता है। |
| [unlink_layer(layer)](#unlink_layer_layer_4) | लेयर का लिंक हटाता है। |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

लिंक समूह आईडी द्वारा लेयर्स प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| link_group_id | short | लिंक समूह आईडी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | लेयर्स एरे। |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

लेयर से जुड़े लिंक समूह आईडी को प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | लेयर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| short | लिंक समूह आईडी। |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

इनपुट लेयर्स को लिंक करता है और LingGroupId लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | लेयर्स। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| short | लिंक समूह आईडी। |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

लेयर का लिंक हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | लेयर। |

