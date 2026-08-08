---
title: "IImageExporterDescriptor"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa el descriptor del exportador de imágenes."
type: docs
weight: 122
url: /es/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Representa el descriptor del exportador de imágenes. El descriptor del exportador se utiliza para superar la necesidad de contener cada instancia del exportador en memoria y los problemas de multihilo.
## Métodos

| Método | Descripción |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado. |
| [createInstance()](#createInstance--) | Crea una nueva instancia del exportador. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | La imagen a exportar. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | La base de opciones. |

**Returns:**
boolean -  true  si el exportador creado por este descriptor puede exportar la imagen especificada al formato de archivo especificado; de lo contrario,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Crea una nueva instancia del exportador.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
