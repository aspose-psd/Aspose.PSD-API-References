---
title: "IImageLoaderDescriptor"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il descrittore del caricatore di immagini che specifica le proprietà del caricatore."
type: docs
weight: 124
url: /it/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Il descrittore del caricatore di immagini che specifica le proprietà del caricatore. Il descrittore del caricatore è usato per superare la necessità di contenere ogni istanza del caricatore di immagini in memoria e i problemi di multithreading.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente usando le  loadOptions . |
| [createInstance()](#createInstance--) | Crea una nuova istanza del caricatore. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente usando le  loadOptions .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | I dettagli del formato file specificati da  loadOptions . Le  loadOptions  possono essere null. |

**Returns:**
boolean -  true  se il caricatore di immagini creato da questo descrittore può leggere l'immagine dallo stream; altrimenti,  false .
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Crea una nuova istanza del caricatore.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
