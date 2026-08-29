---
title: "IImageLoaderDescriptor"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le descripteur du chargeur d'image spécifiant les propriétés du chargeur."
type: docs
weight: 124
url: /fr/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

Le descripteur du chargeur d'image spécifiant les propriétés du chargeur. Le descripteur du chargeur est utilisé pour surmonter la nécessité de contenir chaque instance de chargeur d'image en mémoire et les problèmes de multithreading.
## Méthodes

| Méthode | Description |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant les loadOptions. |
| [createInstance()](#createInstance--) | Crée une nouvelle instance du chargeur. |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant les loadOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les détails du format de fichier spécifiés par loadOptions. Le loadOptions peut être nul. |

**Returns:**
booléen - true si le chargeur d'image créé par ce descripteur peut lire l'image depuis le flux ; sinon, false.
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


Crée une nouvelle instance du chargeur.

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
