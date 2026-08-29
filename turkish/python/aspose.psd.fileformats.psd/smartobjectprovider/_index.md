---
title: "SmartObjectProvider Sınıfı"
type: docs
weight: 1940
url: /tr/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Katmanları gömülü bir akıllı nesneye dönüştürür. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Katmanları gömülü bir akıllı nesneye dönüştürür. |
| embed_all_linked() | Görüntüdeki tüm bağlı akıllı nesneleri gömer. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Kaynak katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur. |
| update_all_modified_content() | Görüntüdeki tüm değiştirilmiş akıllı nesnelerin içeriğini günceller. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Katmanları gömülü bir akıllı nesneye dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer_numbers | int | Katman numaraları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Oluşturulan [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) örneği. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Katmanları gömülü bir akıllı nesneye dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Katmanlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Oluşturulan [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) örneği. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Kaynak katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Kaynak katman. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Klonlanmış [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) örneği. |


