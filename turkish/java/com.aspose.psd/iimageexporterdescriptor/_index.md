---
title: "IImageExporterDescriptor"
second_title: "Java için Aspose.PSD API Referansı"
description: "Görüntü dışa aktarıcı tanımlayıcısını temsil eder."
type: docs
weight: 122
url: /tr/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Görüntü dışa aktarıcı tanımlayıcısını temsil eder. Dışa aktarıcı tanımlayıcı, her dışa aktarıcı örneğinin bellekte tutulması gerekliliğini ve çok iş parçacıklı sorunları aşmak için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Görüntü dışa aktarıcının, kaydetme seçenekleriyle belirtilen görüntüyü belirtilen görüntü formatına dışa aktarabilip aktaramayacağını belirler. |
| [createInstance()](#createInstance--) | Yeni bir dışa aktarıcı örneği oluşturur. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Görüntü dışa aktarıcının, kaydetme seçenekleriyle belirtilen görüntüyü belirtilen görüntü formatına dışa aktarabilip aktaramayacağını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Dışa aktarılacak görüntü. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Seçeneklerin temeli. |

**Returns:**
boolean -  true  eğer bu tanımlayıcı tarafından oluşturulan dışa aktarıcı belirtilen görüntüyü belirtilen dosya biçimine dışa aktarabiliyorsa; aksi takdirde,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Yeni bir dışa aktarıcı örneği oluşturur.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
