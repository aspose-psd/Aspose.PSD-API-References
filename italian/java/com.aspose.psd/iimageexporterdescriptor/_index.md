---
title: "IImageExporterDescriptor"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta il descrittore dell'esportatore di immagini."
type: docs
weight: 122
url: /it/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Rappresenta il descrittore dell'esportatore di immagini. Il descrittore dell'esportatore è usato per superare la necessità di contenere ogni istanza dell'esportatore in memoria e i problemi di multithreading.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio. |
| [createInstance()](#createInstance--) | Crea una nuova istanza dell'esportatore. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'immagine da esportare. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | La base delle opzioni. |

**Returns:**
boolean -  true  se l'esportatore creato da questo descrittore può esportare l'immagine specificata nel formato file specificato; altrimenti,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Crea una nuova istanza dell'esportatore.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
