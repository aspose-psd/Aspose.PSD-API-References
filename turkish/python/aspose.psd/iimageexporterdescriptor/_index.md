---
title: "IImageExporterDescriptor Sınıfı"
type: docs
weight: 1800
url: /tr/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Desteklenen formatı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Görüntü dışa aktarıcının, kaydetme seçenekleriyle belirtilen hedef görüntü formatına belirtilen görüntüyü dışa aktarabilip aktaramadığını belirler. |
| [create_instance()](#create_instance__2) | Yeni bir dışa aktarıcı örneği oluşturur. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Görüntü dışa aktarıcının, kaydetme seçenekleriyle belirtilen hedef görüntü formatına belirtilen görüntüyü dışa aktarabilip aktaramadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Dışa aktarılacak görüntü. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçeneklerin temeli. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>True</c> eğer bu tanımlayıcı tarafından oluşturulan dışa aktarıcı belirtilen görüntüyü belirtilen dosya formatına dışa aktarabiliyorsa; aksi takdirde <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Yeni bir dışa aktarıcı örneği oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Yeni bir dışa aktarıcı örneği. |


