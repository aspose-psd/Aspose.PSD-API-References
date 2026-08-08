---
title: "IImageCreatorDescriptor"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El descriptor del creador de imágenes que especifica las propiedades del creador."
type: docs
weight: 119
url: /es/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

El descriptor del creador de imágenes que especifica las propiedades del creador. El descriptor del creador se utiliza para superar la necesidad de contener cada instancia del creador de imágenes en memoria y los problemas de multithreading.
## Métodos

| Método | Descripción |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Determina si el creador de imágenes puede crear una nueva imagen usando el  imageOptions . |
| [createInstance()](#createInstance--) | Crea una nueva instancia del creador. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Determina si el creador de imágenes puede crear una nueva imagen usando el  imageOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de imagen. |

**Returns:**
boolean -  true  si el creador de imágenes creado por este descriptor puede crear datos de imagen usando el  imageOptions  especificado; de lo contrario,  false .
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Crea una nueva instancia del creador.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
