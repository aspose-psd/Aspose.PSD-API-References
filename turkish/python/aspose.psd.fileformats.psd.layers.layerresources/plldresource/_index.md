---
title: "PlLdResource Sınıfı"
type: docs
weight: 820
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.<br/>            It was replaced by SoLdResource in the Adobe� Photoshop� CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| anti_alias_policy | int | r/w | PSD görüntüsündeki yerleştirilen katmanın anti-alias politikalarını alır veya ayarlar. |
| alt | double | r/w | PSD görüntüsündeki yerleştirilen katmanın alt konumunu alır veya ayarlar. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD dosyasındaki yerleştirilen katmanın sınırlarını alır veya ayarlar. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Yatay ağ noktalarının ölçü birimini alır veya ayarlar. |
| horizontal_mesh_points | double | r/w | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktalarını alır veya ayarlar. |
| is_custom | bool | r/w | Bu örnek eğri stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Doğru ise ağ noktalarını içerir. Yanlış olarak ayarlanırsa ağ noktalarını siler. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Eğri öğelerini alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| sol | double | r/w | PSD dosyasındaki yerleştirilen katmanın sol konumunu alır veya ayarlar. |
| uzunluk | int | r | PlLd kaynağının uzunluğunu bayt cinsinden alır. |
| page_number | int | r/w | PSD dosyasındaki yerleştirilen katmanın sayfa numarasını alır veya ayarlar. |
| perspective | double | r/w | PSD dosyasındaki yerleştirilen katmanın perspektif değerini alır veya ayarlar. |
| perspective_other | double | r/w | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değerini alır veya ayarlar. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD dosyasındaki yerleştirilen katmanın tipini alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| sağ | double | r/w | PSD dosyasındaki yerleştirilen katmanın sağ konumunu alır veya ayarlar. |
| signature | int | r | İmzayı alır. |
| üst | double | r/w | PSD görüntüsündeki yerleştirilen katmanın üst konumunu alır veya ayarlar. |
| total_pages | int | r/w | PSD dosyasındaki yerleştirilen katmanın toplam sayfalarını alır veya ayarlar. |
| transform_matrix | double | r/w | PSD dosyasındaki yerleştirilen katmanın dönüşüm matrisini alır veya ayarlar. |
| u_order | int | r/w | PSD dosyasındaki yerleştirilen katmanın U sıra değerini alır veya ayarlar. |
| unique_id | Guid | r/w | PSD görüntüsündeki yerleştirilen katmanın küresel benzersiz tanımlayıcısını alır veya ayarlar. |
| v_order | int | r/w | PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar. |
| değer | double | r/w | PSD görüntüsündeki yerleştirilen katmanın eğri değerini alır veya ayarlar. |
| version | int | r | PSD dosyasındaki yerleştirilen katmanın sürümünü alır, genellikle 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Dikey ağ noktalarının ölçü birimini alır veya ayarlar. |
| vertical_mesh_points | double | r/w | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktalarını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | PlLD kaynağını belirtilen akış konteynerine kaydeder. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

PlLD kaynağını belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

