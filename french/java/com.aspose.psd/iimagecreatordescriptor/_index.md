---
title: "IImageCreatorDescriptor"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le descripteur du créateur d'image spécifiant les propriétés du créateur."
type: docs
weight: 119
url: /fr/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

Le descripteur du créateur d'image spécifiant les propriétés du créateur. Le descripteur du créateur est utilisé pour surmonter la nécessité de contenir chaque instance du créateur d'image en mémoire et les problèmes de multithreading.
## Méthodes

| Méthode | Description |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | Détermine si le créateur d'image peut créer une nouvelle image en utilisant les imageOptions. |
| [createInstance()](#createInstance--) | Crée une nouvelle instance du créateur. |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


Détermine si le créateur d'image peut créer une nouvelle image en utilisant les imageOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'image. |

**Returns:**
booléen - true si le créateur d'image créé par ce descripteur peut créer des données d'image en utilisant les imageOptions spécifiés ; sinon, false.
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


Crée une nouvelle instance du créateur.

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
