---
title: "IImageLoaderDescriptor"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El descriptor del cargador de imágenes que especifica las propiedades del cargador."
type: docs
weight: 124
url: /es/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

El descriptor del cargador de imágenes que especifica las propiedades del cargador. El descriptor del cargador se usa para superar la necesidad de contener cada instancia del cargador de imágenes en memoria y los problemas de multihilo.
## Métodos

| Método | Descripción |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando las  loadOptions . |
| [createInstance()](#createInstance--) | Crea una nueva instancia del cargador. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Determina si el cargador de imágenes puede leer una nueva imagen del flujo especificado y opcionalmente usando las  loadOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Los detalles del formato de archivo especificados por  loadOptions . El  loadOptions  puede ser nulo. |

**Returns:**
boolean -  true  si el cargador de imágenes creado por este descriptor puede leer la imagen del flujo; de lo contrario,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Crea una nueva instancia del cargador.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
