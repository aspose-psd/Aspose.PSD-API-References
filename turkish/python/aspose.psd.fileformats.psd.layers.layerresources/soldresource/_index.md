---
title: "SoLdResource Sınıfı"
type: docs
weight: 930
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---

**Summary:** Defines the SoLdResource class that contains information about a smart object layer in a PSD file.<br/>            Is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLdResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [SoLdResource()](#SoLdResource__1) | Yeni bir [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) sınıfının yeni bir örneğini başlatır.<br/>            Bu varsayılan yapıcı, [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/) tarafından kullanılmak üzere tasarlanmıştır.<br/>            SoLdResource sınıflarını oluşturmak için [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) kullanın. |
| [SoLdResource(unique_id, is_custom, has_comp_info)](#SoLdResource_unique_id_is_custom_has_comp_info_2) | Yeni bir [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) sınıfının yeni bir örneğini başlatır.<br/>            Hazır bir örnek elde etmek için Items özelliğini ayarlamak veya InitializeItems() metodunu çağırmak gerekir.<br/>            Bu yapıcı, [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) tarafından kullanılmak üzere tasarlanmıştır.<br/>            ve birim testlerinde.<br/>            SoLdResource sınıflarını oluşturmak için [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) kullanın. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür araç bilgi anahtarı: 'SoLd'. |
| anti_alias_policy | int | r/w | PSD görüntüsündeki akıllı nesne katman verisinin anti-alias politikası alır veya ayarlar. |
| alt | double | r/w | PSD görüntüsündeki yerleştirilen katmanın alt konumunu alır veya ayarlar. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD dosyasındaki yerleştirilen katmanın sınırlarını alır veya ayarlar. |
| comp | int | r/w | PSD dosyasındaki akıllı nesne katman verisinin comp değerini alır veya ayarlar.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Akıllı Nesnelerde Katman Kompozisyonları</see> |
| comp_id | int | r/w | Çocuk belge için şu anda seçili comp'in kimliğini alır veya ayarlar; hiçbir şey seçili değilse -1 olur.<br/>            Comp'lar, tasarımcıların oluşturabileceği bir sayfa düzeninin kompozisyonlarıdır. Katman comp'larını kullanarak, tek bir Adobe® Photoshop® dosyasında bir düzenin birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz.<br/>            Katman comp'i, Katmanlar panelinin bir durumunun anlık görüntüsüdür. Katman comp'leri üç tür katman seçeneğini kaydeder ancak bu özellik, PSD dosyasındaki akıllı nesne katmanı için Katman Comp seçim tanımlayıcısını alır.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Akıllı Nesnelerde Katman Kompozisyonları</see> |
| crop | int | r/w | PSD görüntüsündeki akıllı nesne katman verisinin kırpmasını alır veya ayarlar. |
| duration_denominator | int | r/w | Süre paydasını alır veya ayarlar. |
| duration_numerator | int | r/w | Süre payını alır veya ayarlar. |
| frame_count | int | r/w | PSD dosyasındaki akıllı nesne katman verisinin kare sayısını alır veya ayarlar. |
| frame_step_denominator | int | r/w | Kare adım paydasını alır veya ayarlar. |
| frame_step_numerator | int | r/w | Kare adım payını alır veya ayarlar. |
| yükseklik | double | r/w | Yüksekliği alır veya ayarlar. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Yatay ağ noktalarının ölçü birimini alır veya ayarlar. |
| horizontal_mesh_points | double | r/w | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktalarını alır veya ayarlar. |
| is_custom | bool | r/w | Bu örnek eğri stilinin özel olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Doğru ise ağ noktalarını içerir. Yanlış olarak ayarlanırsa ağ noktalarını siler. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | PSD dosyasındaki akıllı nesne katman verisinin tanımlayıcı öğelerini alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| sol | double | r/w | PSD dosyasındaki yerleştirilen katmanın sol konumunu alır veya ayarlar. |
| uzunluk | int | r | Akıllı nesne kaynağının uzunluğunu bayt olarak alır. |
| non_affine_transform_matrix | double | r/w | PSD dosyasındaki akıllı nesne katman verisinin doğrusal olmayan dönüşüm matrisini alır veya ayarlar. |
| original_comp_id | int | r | Alt belge için şu anda seçili olan Comp'in orijinal kimliğini alır; hiçbir şey seçilmemişse -1 olur.<br/>            Bu özellik, PSD dosyasındaki akıllı nesne katmanı için orijinal katman Comp seçim tanımlayıcısını alır.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Akıllı Nesnelerde Katman Bileşenleri</see> |
| page_number | int | r/w | PSD dosyasındaki akıllı nesne katman verisinin sayfa numarasını alır veya ayarlar. |
| perspective | double | r/w | PSD dosyasındaki yerleştirilen katmanın perspektif değerini alır veya ayarlar. |
| perspective_other | double | r/w | PSD dosyasındaki yerleştirilen katmanın diğer perspektif değerini alır veya ayarlar. |
| placed_id | Guid | r/w | PSD görüntüsündeki bu akıllı nesne katman verisinin benzersiz tanımlayıcısını alır veya ayarlar. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD dosyasındaki akıllı nesne katman verisinin türünü alır veya ayarlar. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| resolution | double | r/w | PSD dosyasındaki akıllı nesne katman verisinin çözünürlüğünü alır veya ayarlar. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | PSD dosyasındaki akıllı nesne katman verisinin çözünürlük ölçü birimini alır veya ayarlar. |
| sağ | double | r/w | PSD dosyasındaki yerleştirilen katmanın sağ konumunu alır veya ayarlar. |
| signature | int | r | İmzayı alır. |
| üst | double | r/w | PSD görüntüsündeki yerleştirilen katmanın üst konumunu alır veya ayarlar. |
| total_pages | int | r/w | PSD dosyasındaki akıllı nesne katman verisinin toplam sayfa sayısını alır veya ayarlar. |
| transform_matrix | double | r/w | PSD dosyasındaki akıllı nesne katman verisinin dönüşüm matrisini alır veya ayarlar. |
| u_order | int | r/w | PSD dosyasındaki yerleştirilen katmanın U sıra değerini alır veya ayarlar. |
| unique_id | Guid | r/w | PSD görüntüsündeki akıllı nesne katman verisinin [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) küresel benzersiz tanımlayıcısını alır veya ayarlar. |
| v_order | int | r/w | PSD dosyasındaki yerleştirilen katmanın V sıra değerini alır veya ayarlar. |
| değer | double | r/w | PSD görüntüsündeki yerleştirilen katmanın eğri değerini alır veya ayarlar. |
| version | int | r | PSD dosyasındaki yerleştirilen katmanın sürümünü alır, genellikle 3-5. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Dikey ağ noktalarının ölçü birimini alır veya ayarlar. |
| vertical_mesh_points | double | r/w | PSD dosyasındaki yerleştirilen katmanın yatay ağ noktalarını alır veya ayarlar. |
| width | double | r/w | Genişliği alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Akıllı nesne kaynağını belirtilen akış konteynerine kaydeder. |


### Constructor: SoLdResource() {#SoLdResource__1}


```
 SoLdResource() 
```

Yeni bir [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) sınıfının yeni bir örneğini başlatır.<br/>            Bu varsayılan yapıcı, [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/) tarafından kullanılmak üzere tasarlanmıştır.<br/>            SoLdResource sınıflarını oluşturmak için [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) kullanın.

### Constructor: SoLdResource(unique_id, is_custom, has_comp_info) {#SoLdResource_unique_id_is_custom_has_comp_info_2}


```
 SoLdResource(unique_id, is_custom, has_comp_info) 
```

Yeni bir [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) sınıfının yeni bir örneğini başlatır.<br/>            Hazır bir örnek elde etmek için Items özelliğini ayarlamak veya InitializeItems() metodunu çağırmak gerekir.<br/>            Bu yapıcı, [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) tarafından kullanılmak üzere tasarlanmıştır.<br/>            ve birim testlerinde.<br/>            SoLdResource sınıflarını oluşturmak için [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| unique_id | Guid | Akıllı nesne katman verisinin benzersiz tanımlayıcısı [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/). |
| is_custom | bool | eğer <c>true</c> olarak ayarlanırsa [is custom]. |
| has_comp_info | bool | eğer <c>true</c> olarak ayarlanırsa [has comp information]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Akıllı nesne kaynağını belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

