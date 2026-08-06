---
title: "IImageExporterDescriptor"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente le descripteur de l'exportateur d'image."
type: docs
weight: 122
url: /fr/java/com.aspose.psd/iimageexporterdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageExporterDescriptor extends IImageDescriptor
```

Représente le descripteur d'exportateur d'image. Le descripteur d'exportateur est utilisé pour surmonter la nécessité de contenir chaque instance d'exportateur en mémoire et les problèmes de multithreading.
## Méthodes

| Méthode | Description |
| --- | --- |
| [canExport(Image image, ImageOptionsBase optionsBase)](#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-) | Détermine si l'exportateur d'image peut exporter l'image spécifiée au format d'image spécifié par les options d'enregistrement. |
| [createInstance()](#createInstance--) | Crée une nouvelle instance d'exportateur. |
### canExport(Image image, ImageOptionsBase optionsBase) {#canExport-com.aspose.psd.Image-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canExport(Image image, ImageOptionsBase optionsBase)
```


Détermine si l'exportateur d'image peut exporter l'image spécifiée au format d'image spécifié par les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | L'image à exporter. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | La base des options. |

**Returns:**
booléen -  true  si l'exportateur créé par ce descripteur peut exporter l'image spécifiée au format de fichier spécifié ; sinon,  false .
### createInstance() {#createInstance--}
```
public abstract IImageExporter createInstance()
```


Crée une nouvelle instance d'exportateur.

**Returns:**
[IImageExporter](../../com.aspose.psd/iimageexporter) - A new exporter instance.
