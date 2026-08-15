---
title: "IImageCreatorDescriptor Sınıfı"
type: docs
weight: 1770
url: /tr/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Desteklenen formatı alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Görüntü oluşturucunun <paramref name="imageOptions" /> kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler. |
| [create_instance()](#create_instance__2) | Yeni bir oluşturucu örneği oluşturur. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Görüntü oluşturucunun <paramref name="imageOptions" /> kullanarak yeni bir görüntü oluşturup oluşturamayacağını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>True</c> eğer bu tanımlayıcı tarafından oluşturulan görüntü oluşturucu belirtilen <paramref name="imageOptions" /> kullanarak görüntü verisi oluşturabiliyorsa; aksi takdirde <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Yeni bir oluşturucu örneği oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Yeni bir oluşturucu örneği. |


