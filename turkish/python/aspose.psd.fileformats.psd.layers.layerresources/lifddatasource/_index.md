---
title: "LiFdDataSource Sınıfı"
type: docs
weight: 510
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---

**Summary:** Defines the liFD data source class in PSD File that contains information about an embedded file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFdDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LiFdDataSource()](#LiFdDataSource__1) | Yeni bir [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) sınıfının örneğini başlatır. |
| [LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | Yeni bir [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | PSD varlığının kilitli olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Varlık kilit durumu, Adobe® Photoshop® СС Kütüphaneleri varlıkları için. |
| asset_mod_time | double | r/w | Adobe® Photoshop® СС Kütüphaneleri varlıkları için varlık değiştirilme zamanını alır veya ayarlar. |
| child_doc_id | string | r/w | Lnk2 / LnkE Adobe® Photoshop® kaynağının liFE veya liFD veri kaynağındaki alt belge tanımlayıcısını alır veya ayarlar. |
| comp_id | int | r/w | Alt belge için şu anda seçili olan kompozisyonun kimliğini alır veya ayarlar; hiçbir şey seçili değilse bu değer -1 olur.<br/>            Kompozisyonlar, tasarımcıların oluşturabileceği bir sayfa düzeninin bileşimleridir. Katman kompozisyonlarını kullanarak, tek bir Adobe® Photoshop® dosyasında bir düzenin birden çok sürümünü oluşturabilir, yönetebilir ve görüntüleyebilirsiniz.<br/>            Katman panelinin bir durumunun anlık görüntüsü bir Layer Comp'tir. Layer Comp'ler üç tür katman seçeneğini kaydeder ancak bu özellik Smart Objects için Layer Comp seçim kimliğini alır.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| veri | byte | r/w | PSD dosyasındaki gömülü akıllı nesne verisini alır veya ayarlar. |
| file_creator | string | r/w | PSD formatındaki LnkE / Lnk2 kaynağında dosya oluşturucusunu alır veya ayarlar. |
| file_type | string | r/w | Adobe® Photoshop® Lnk2 / LnkE kaynağının içerdiği veya bağlandığı gömülü veya harici dosyanın türünü alır veya ayarlar. |
| has_file_open_descriptor | bool | r/w | Bu bağlantı veri kaynağının dosya açık tanımlayıcısına (CompId ve OriginalCompId) sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| is_library_link | bool | r | Bu PSD bağlantı veri kaynağının Adobe® Photoshop® СС Kütüphane öğesine bağlanıp bağlanmadığını gösteren bir değeri alır. |
| uzunluk | long | r | Bağlantı veri kaynağının uzunluğunu bayt cinsinden alır. |
| original_comp_id | int | r | Çocuk belge için şu anda seçili olan Comp'in orijinal kimliğini alır; hiçbiri seçilmemişse -1 olur.<br/>            Bu özellik, Akıllı Nesneler için orijinal katman Comp seçim tanımlayıcısını alır.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Akıllı Nesnelerde Katman Kompozisyonları</see> |
| original_file_name | string | r | Adobe® Photoshop® global bağlantı kaynağındaki veri kaynağının orijinal dosya adını alır. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Adobe® Photoshop® global bağlantı veri kaynağı türünü alır; aşağıdakilerden biri veya hiçbiri olabilir:<br/>            PSD Lnk2Resource ile eşleşen gömülü bağlı dosya liFD<br/>            PSD LnkeResource ile eşleşen harici bağlı dosya liFE<br/>            Bağlı dosya takma adı liFA |
| unique_id | Guid | r | PSD bağlantı kaynağındaki veri kaynağının global benzersiz tanımlayıcısını alır. |
| version | int | r | PSD LnkE / Lnk2 kaynağındaki veri kaynağının sürümünü alır. |


### Constructor: LiFdDataSource() {#LiFdDataSource__1}


```
 LiFdDataSource() 
```

Yeni bir [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) sınıfının örneğini başlatır.

### Constructor: LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

Yeni bir [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| version | int | Sürüm. |
| unique_id | Guid | Benzersiz tanımlayıcı. |
| original_file_name | string | Orijinal dosyanın adı. |
| file_type | string | Dosyanın türü. |
| file_creator | string | Dosya oluşturucu. |

